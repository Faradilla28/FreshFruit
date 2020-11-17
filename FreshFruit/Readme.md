# FreshFruit
Aplikasi ini mencakup berapa banyak buah yang bisa dimasukan kedalam keranjang buah.

# Scope & Functionalities
- User dapat menambahkan buah ke keranjang.
- User bisa menekan tombol add untuk menambahkan buah.
- User mendapat info "ops, keranjang penuh " jika buah yang dimasukkan sudah lebih dari yang ditentukan.

## How Does it works?

Diawali dari method 'MainWindow' pada class MainWindow.xaml.cs, cara mendeskripsikannya blablabla,,,

```csharp
 public MainWindow()
        {
            InitializeComponent();

            Bucket keranjangBuah = new Bucket(2);
            BucketController bucketController = new BucketController(keranjangBuah, this);

            toni = new Seller("toni", bucketController);

            ListBoxBucket.ItemsSource = keranjangBuah.findAll();
        }
```
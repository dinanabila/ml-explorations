# Notes

## Pengaruh hubungan linear fitur dan target

Kalau hubungan antara masing-masing fitur dengan target nya **linear**, performa model Linear Regression bisa **naik**. Salah satu cara yang bisa dicoba untuk melinearkan hubungan yang tadinya tidak linear adalah dengan menggunakan **[log transformation](https://github.com/dinanabila/ml-explorations/blob/main/Linear%20Regression/log_transformation.ipynb)**. Alternatif lainnya bisa dengan sqrt, kuadrat, tergantung bagaimana distribusi data nya.


## Multikolinearitas
Multikolinearitas dapat menjadi masalah dalam Linear Regression karena dapat membuat nilai koefisien menjadi tidak stabil ketika terjadi perubahan pada data training.

Ketika diuji menggunakan test data yang sama, terdapat perbedaan pada hasil evaluasi antara model yang dilatih menggunakan seluruh fitur dan model yang dilatih menggunakan fitur dengan multikolinearitas yang telah dikurangi.

Dalam eksperimen pada dataset di [notebook ini](https://github.com/dinanabila/ml-explorations/blob/main/Linear%20Regression/multicollinearity.ipynb), model yang menggunakan fitur dengan multikolinearitas yang lebih rendah menghasilkan nilai MAE pada test set yang lebih baik dibandingkan model yang masih menggunakan fitur dengan multikolinearitas yang kuat.

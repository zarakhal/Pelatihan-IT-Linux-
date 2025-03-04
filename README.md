# Pelatihan-IT-Linux-
1. Membuat folder lalu membuka atau mengaksesnya.

```sh
mkdir artists_who_can_sing && cd artists_who_can_sing
```

2. Unduh file zip menggunakan wget.

```sh
wget --no-check-certificate 'https://drive.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut' -O tutorials.zip
```
3. Unzip file yang sudah didownload dan dimasukkan ke folder baru.

```sh
unzip tutorials.zip -d singing_tutorials
```
4. Menampilkan seluruh file

```sh
ls -la
```

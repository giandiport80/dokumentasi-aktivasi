## AKTIVASI WINDOWS

### Aktivasi windows (versi menyesuaikan)
kunjungi web microsoft atau cari kms client

https://docs.microsoft.com/en-us/windows-server/get-started/kmsclientkeys

contoh ini adalah product key untuk windows 10 pro: `W269N-WFGWX-YVC9B-4J6C9-T83GX`

masuk ke cmd, dengan run as adminstrator, lalu ketikkan kode berikut

```
slmgr /ipk <product-key>
```

```
slmgr /skms kms8.msguides.com
```

```
slmgr /ato
```

### Menghilangkan tulisan activate windows

atau kita bisa menghilangkan tulisan activate windows

copy code berikut

```
@echo off taskkill/F/IM explorer.exe explorer.exe exit
```

simpan dengan remove.bat

kemudian jalankan filenya dengan run as administrator
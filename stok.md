### URL

| Kode | URL |
| ---- | --- |
| Production | https://api.nmwclinic.co.id/api/pos/pos/insert-stock |
| Sandbox | https://api-sandbox.nmwclinic.co.id/api/pos/pos/insert-stock |

### METHODE

POST

### SORCECODE

``` php
<?php

$curl = curl_init();

curl_setopt_array($curl, array(
  CURLOPT_URL => 'http://127.0.0.1:8000/api/pos/insert-stock',
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => '',
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 0,
  CURLOPT_FOLLOWLOCATION => true,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => 'POST',
  ));

$response = curl_exec($curl);

curl_close($curl);
echo $response;
```

### PARAMETER

| Field | Type | Desc |
| ----- | ---- | ---- |
| sumber | 'nullable' | Sumber |
| noTransaksi | 'nullable' | Nomer Transaksi |
| users | 'numeric' | Users |
| karyawan | 'nullable' | Karyawan |
| uraian | 'nullable' | Uraian Stock |
| catatan | 'nullable' | Catatan Stock |
| totalTransaksi | 'numeric' | Total Transaksi |
| createStock | 'numeric' | Create Stock |
| modifyStock | 'numeric' | Modify Stock |
| totalKas | 'numeric' | Total Kas|
| totalKartuDebit | 'numeric' | Total Kartu Debit |
| totalKartuKredit | 'numeric' | Total Kartu Kredit |
| noKartuDebit | 'numeric' | Nomer Kartu Debit |
| namaDebit | 'nullable' | Nama Debit |
| bankDebit | 'nullable' | Bank Debit |
| noKartuKredit | 'nullable' | Nomer Kartu Kredit |
| namaKredit | 'nullable' | Nama Kredit |
| bankKredit | 'nullable' | Bank Kredit |
| totalBayar | 'numeric' | Total Bayar |
| totalSisa  | 'numeric' | Total Sisa |
| sudpid | 'nullable' | SUDPID |
| totalDp | 'numeric' | Total DP |
| totalTransfer | 'numeric' | Total Transfer |
| bankTransfer | 'nullable' | Transfer Bank |
| namaTransfer | 'nullable' | Nama Transfer |
| noTransfer | 'nullable' | Nomer Transfer |
| totalVoucher | 'nullable' | Total Voucher |
| noVoucher | 'nullable' | Nomer Voucher |
| programVoucher | 'nullable' | Program Voucher |
| namaVoucher | 'nullable' | Nama Voucher |
| doctor | 'nullable' | Dokter |
| branch | 'nullable' | Branch |
| tidakBawaKartu | 'numeric' | Tidak Bawa Kartu |
| kreditJumlahCicilan | 'numeric' | Kredit Jumlah Cicilan |
| kreditCicilanPerbulan | 'numeric' | Kredit Cicilan Perbulan |
| jenisKredit | 'nullable' | Jenis Kredit |
| jenisDebit | 'nullable' | Jenis Debit |
| sudp1 | 'numeric' | SUDP1 |
| sudpid2 | 'nullable' | SUDPID2 |
| sudp2 | 'numeric' | SUDP2 |
| sudpid3 | 'nullable' | SUDPID3 |
| sudp3 | 'numeric' | SUDP3 |
| potonganStok | 'nullable' | Potongan Stock |
| rekamMedis | 'nullable' | Rekam Medis |
| dariMedikaApps | 'nullable' | Dari Medika Apps |
| totalMedika | 'nullable' | Total Medika |
| noReffMedika | 'nullable' | No Reff Medika |
| statusKirim | 'nullable' | Status Kirim |
| address | 'nullable' | Address |
| totalTada | 'nullable' | Total Tada |
| teman | 'nullable' | Teman |
| jenisMerchant | 'nullable' | Jenis Merchant |
| noMerchant | 'nullable' | Nomer Merchant |
| jumlahMerchant | 'nullable' | Jumlah Merchant |
| noIP | 'nullable' | Nomer IP |
| biayaKirim | 'nullable' | Biaya Kirim |
| konsinyasi | 'nullable' | Konsinyasi |
| nilaiPajak | 'nullable' | Nilai Pajak |
| jenisOnline | 'nullable' | Jenis Online |
| attention | 'nullable' | Attention |
| fakturPajak | 'nullable' | Faktur Pajak |
| rekHutang | 'nullable' | Rekening Hutang |
| admin1 | 'nullable' | Admin 1 |
| admin2 | 'nullable' | Admin 2 |
| konul | 'nullable' | Konul |
| konsulKemarin | 'nullable' | Konsul Kemarin |
| sunodkr | 'nullable' | SUNODKR |
| admin3 | 'nullable' | Admin3 |
| insider | 'nullable' | Insider |
| jenisDp | 'nullable' | Jenis DP |
| adminFU | 'nullable' | Admin FU |
| farmasi | 'nullable' | Farmasi |
| farmasiAsisten | 'nullable' | Farmasi Asisten |
| jenisFu | 'nullable' | Jenis FU |
| tanggalFu | 'date' | Tanggal FU |
| suIdFu | 'nullable' | SUIDFU |
| salesMarketing | 'nullable' | Sales Marketing | 

### RESPONSE (SUCESS)

``` json
{
    "status": true,
    "date": "14-12-2021",
    "message": "Data berhasil dimuat",
    "data": {
        "headerStok": {
            "id": 399845
        },
        "stockDetail": {
            "id": 3114131
        }
    }
}
```

### RESPONSE (GAGAL)

```json

```

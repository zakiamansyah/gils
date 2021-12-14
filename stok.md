### URL

| Kode | URL |
| ---- | --- |
| Production | https://api.nmwclinic.co.id/api/pos/pos/get-item |
| Sandbox | https://api-sandbox.nmwclinic.co.id/api/pos/pos/get-item |

### METHODE

GET

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
  CURLOPT_POSTFIELDS => array('sumber' => 'IP','noTransaksi' => 'MI-PY23388427395','tanggal' => '2021-02-05','users' => '63271','karyawan' => '20093','uraian' => 'Penyesuaian Barang','catatan' => '','totalTransaksi' => '40000','createStock' => '95','modifyStock' => '1','totalKas' => '0','totalKartuDebit' => '0','totalKartuKredit' => '0','noKartuDebit' => '421408000123455','namaDebit' => 'ZakiHAJH','bankDebit' => 'BCA','noKartuKredit' => '','namaKredit' => '','bankKredit' => '','totalBayar' => '500000','totalSisa' => '0','sudpid' => '','totalDp' => '0','totalTransfer' => '0','bankTransfer' => '','namaTransfer' => '','noTransfer' => '','totalVoucher' => '0','noVoucher' => '','programVoucher' => '','namaVoucher' => '','doctor' => '','branch' => '1','tidakBawaKartu' => '0','kreditJumlahCicilan' => '0','kreditCicilanPerbulan' => '0','jenisKredit' => '','jenisDebit' => 'DEBIT','sudp1' => '0','sudpid2' => '','sudp2' => '0','sudpid3' => '','sudp3' => '0','potonganStok' => '','rekamMedis' => 'COMPLETED','dariMedikaApps' => '0','totalMedika' => '0','noReffMedika' => '','statusKirim' => '','address' => 'TEST INSERT STOK','totalTada' => '150000','teman' => '','jenisMerchant' => '','noMerchant' => '','jumlahMerchant' => '0','noIP' => '','biayaKirim' => '0','konsinyasi' => '0','nilaiPajak' => '0','jenisOnline' => '0','attention' => 'COBAIN','fakturPajak' => '','rekHutang' => '','admin1' => '','admin2' => '','konul' => '0','konsulKemarin' => '0','sunodkr' => '','admin3' => '','insider' => '','jenisDp' => '','adminFU' => '','farmasi' => '','farmasiAsisten' => '','jenisFu' => '0','tanggalFu' => '','suIdFu' => '','salesMarketing' => '0','from' => '','id' => '[{"from": "IL", "id" : 924, "urutan": 65, "branch": 1, "qty": 100, "out": 2, "satuan": 20, "out": 2, "price": 80000, "discount": 0, "arrival": 0, "discountPercent": 0, "karyawan": 238502, "tindakan": 0, "pending": 0, "noreff": 0, "doctor": 238502, "catatanKoli": 0, "discountPercent2": 0, "discount2": 0, "pengulangan": 0, "lantai2": 0, "cetak": 0, "idPromo": 0, "price0": 0, "dariPaket": 0, "userRubahDiscount": 0, "priority": 0, "nota": 0, "qtpakai": 0, "sopid": 0, "prdid": 0, "idPotongStok": 0, "sodurutan": 0, "pointKeluar": 0, "qtyIkutKepala": 0, "barisKepala": 0, "voucherId": 0, "urutanAwal": 10 , "referal": 0, "operator2":0}]','urutan' => '','branch' => '','qty' => '','out' => '','satuan' => '','price' => '','discount' => '','arrival' => '','discountPercent' => '','karyawan' => '','tindakan' => '','pending' => '','noreff' => '','doctor' => '','catatanKoli' => '','discountPercent2' => '','discount2' => '','pengulangan' => '','lantai2' => '','cetak' => '','idPromo' => '','price0' => '','dariPaket' => '','userRubahDiscount' => '','priority' => '','nota' => '','tindakan' => '','qtpakai' => '','sopid' => '','prdid' => '','idPotongStok' => '','sodurutan' => '','pointKeluar' => '','qtyIkutKepala' => '','barisKepala' => '','voucherId' => '','urutanAwal' => '','referal' => '','operator2' => ''),
));

$response = curl_exec($curl);

curl_close($curl);
echo $response;
```

### PARAMETER

| Field | Type | Desc | 
| ----- | ---- | ---- |
| sumber | 'nullable' | Name Item/Name Products |
| noTransaksi | 'nullable' |
| users | 'numeric' |
| karyawan | 'nullable' |
| uraian | 'nullable' |
| catatan | 'nullable' |
| totalTransaksi | 'numeric' |
| createStock | 'numeric' |
| modifyStock | 'numeric' |
| totalKas | 'numeric' |
| totalKartuDebit | 'numeric' |
| totalKartuKredit | 'numeric' |
| noKartuDebit | 'numeric' |
| namaDebit | 'nullable' |
| bankDebit | 'nullable' |
| noKartuKredit | 'nullable' |
| namaKredit | 'nullable' |
| bankKredit | 'nullable' |
| totalBayar | 'numeric' |
| totalSisa  | 'numeric' |
| sudpid | 'nullable' |
| totalDp | 'numeric' |
| totalTransfer | 'numeric' |
| bankTransfer | 'nullable' |
| namaTransfer | 'nullable' |
| noTransfer | 'nullable' |
| totalVoucher | 'nullable' |
| noVoucher | 'nullable' |
| programVoucher | 'nullable' |
| namaVoucher | 'nullable' |
| doctor | 'nullable' |
| branch | 'nullable' |
| tidakBawaKartu | 'numeric' |
| kreditJumlahCicilan | 'numeric' |
| kreditCicilanPerbulan | 'numeric' |
| jenisKredit | 'nullable' |
| jenisDebit | 'nullable' |
| sudp1 | 'numeric' |
| sudpid2 | 'nullable' |
| sudp2 | 'numeric' |
| sudpid3 | 'nullable' |
| sudp3 | 'numeric' |
| potonganStok | 'nullable' |
| rekamMedis | 'nullable' |
| dariMedikaApps | 'nullable' |
| totalMedika | 'nullable' |
| noReffMedika | 'nullable' |
| statusKirim | 'nullable' |
| address | 'nullable' |
| totalTada | 'nullable' |
| teman | 'nullable' |
| jenisMerchant | 'nullable' |
| noMerchant | 'nullable' |
| jumlahMerchant | 'nullable' |
| noIP | 'nullable' |
| biayaKirim | 'nullable' |
| konsinyasi | 'nullable' |
| nilaiPajak | 'nullable' |
| jenisOnline | 'nullable' |
| attention | 'nullable' |
| fakturPajak | 'nullable' |
| rekHutang | 'nullable' |
| admin1 | 'nullable' |
| admin2 | 'nullable' |
| konul | 'nullable' |
| konsulKemarin | 'nullable' |
| sunodkr | 'nullable' |
| admin3 | 'nullable' |
| insider | 'nullable' |
| jenisDp | 'nullable' |
| adminFU | 'nullable' |
| farmasi | 'nullable' |
| farmasiAsisten | 'nullable' |
| jenisFu | 'nullable' |
| tanggalFu | 'date' |
| suIdFu | 'nullable' |
| salesMarketing | 'nullable' |

### RESPONSE (SUCESS)

``` json
{
    "status": true,
    "date": "13-12-2021",
    "message": "Data berhasil dimuat",
    "data": {
        "headerStok": {
            "id": 399842,
            "data": {
                "SUSUMBER": "IP",
                "SUNOTRANSAKSI": "MI-PY23388427395",
                "SUTANGGAL": "2021-02-05",
                "SUKONTAK": "63271",
                "SUKARYAWAN": null,
                "SUURAIAN": "Penyesuaian Barang",
                "SUCATATAN": null,
                "SUTOTALTRANSAKSI": "40000",
                "SUCREATEU": "95",
                "SUMODIFU": "1",
                "SUMODIFD": null,
                "SUTOTALKAS": "0",
                "SUTOTALKARTUDEBIT": "0",
                "SUTOTALKARTUKREDIT": "0",
                "SUNOKARTUDEBIT": "421408000123455",
                "SUNAMADEBIT": "ZakiHAJH",
                "SUBANKDEBIT": "BCA",
                "SUNOKARTUKREDIT": null,
                "SUNAMAKREDIT": null,
                "SUBANKKREDIT": null,
                "SUTOTALBAYAR": "500000",
                "SUTOTALSISA": "0",
                "SUDPID": null,
                "SUTOTALDP": "0",
                "SUTOTALTRANSFER": "0",
                "SUBANKTRANSFER": null,
                "SUNAMATRANSFER": null,
                "SUNOTRANSFER": null,
                "SUTOTALVOUCHER": "0",
                "SUNOVOUCHER": null,
                "SUPROGRAMVOUCHER": null,
                "SUNAMAVOUCHER": null,
                "SUDOKTER": null,
                "SUCABANG": null,
                "SUTIDAKBAWAKARTU": "0",
                "SUKREDITJUMLAHCICILAN": "0",
                "SUKREDITCICILANPERBULAN": "0",
                "SUKREDITJENIS": null,
                "SUDEBITJENIS": "DEBIT",
                "SUDP1": "0",
                "SUDPID2": null,
                "SUDP2": "0",
                "SUDPID3": null,
                "SUDP3": "0",
                "SUIDPOTONGSTOK": null,
                "SUREKAMMEDIS": "COMPLETED",
                "SUDARIMEDIKAAPPS": "0",
                "SUTOTALMEDIKA": "0",
                "SUNOREFFMEDIKA": null,
                "SUSTATUSKIRIM": null,
                "SUALAMAT": "TEST INSERT STOK",
                "SUTOTALTADA": "150000",
                "SUTEMAN": null,
                "SUMERCHANTJENIS": null,
                "SUMERCHANTNO": null,
                "SUMERCHANTJUMLAH": "0",
                "SUNOIP": null,
                "SUBIAYAKIRIM": "0",
                "SUKONSINYASI": "0",
                "SUNILAIPAJAK": "0",
                "SUJENISONLINE": "0",
                "SUATTENTION": "COBAIN",
                "SUNOFAKTURPAJAK": null,
                "SUREKHUTANG": null,
                "SUADMIN1": null,
                "SUADMIN2": null,
                "SUKONUL": "0",
                "SUKONSULKEMARIN": "0",
                "SUNODKR": null,
                "SUADMIN3": null,
                "SUINSIDER": null,
                "SUJENISDP": null,
                "SUADMINFU": null,
                "SUFARMASI": null,
                "SUFARMASIASISTEN": null,
                "SUJENISFU": "0",
                "SUTANGGALFU": null,
                "SUIDFU": null,
                "SUSALESMARKETING": "0"
            }
        },
        "stockDetail": {
            "id": 3114129,
            "data": {
                "SDSUMBER": "IL",
                "SDIDSU": 399842,
                "SDITEM": 924,
                "SDURUTAN": 65,
                "SDGUDANG": 1,
                "SDMASUK": 100,
                "SDKELUAR": 2,
                "SDKELUARD": 2,
                "SDSATUAN": 20,
                "SDSATUAND": 20,
                "SDHARGA": 80000,
                "SDDISKON": 0,
                "SDKEDATANGAN": 0,
                "SDDISKONPERSEN": 0,
                "SDKARYAWAN": 238502,
                "SDIDTINDAKAN1": 0,
                "SDPENDING": 0,
                "SDNOREF": 0,
                "SDDOKTER": 238502,
                "SDCATATANKOLI": 0,
                "SDDISKONPERSEN2": 0,
                "SDDISKON2": 0,
                "SDPENGULANGAN": 0,
                "SDLANTAI2": 0,
                "SDCETAK": 0,
                "SDIDPROMO": 0,
                "SDHARGA0": 0,
                "SDDARIPAKET": 0,
                "SDUSERRUBAHDISKON": 0,
                "SDPRIORITAS": 0,
                "SDNOTADA": 0,
                "SDTINDAKAN": 0,
                "SDQTPAKAI": 0,
                "SDSODID": 0,
                "SDPRDID": 0,
                "SDIDPOTONGSTOK": 0,
                "SDSODURUTAN": 0,
                "SDPOINTKELUAR": 0,
                "SDQTYIKUTKEPALA": 0,
                "SDBARISKEPALA": 0,
                "SDVOUCERID": 0,
                "SDURUTANAWAL": 10,
                "SDREFERAL": 0,
                "SDOPERATOR2": 0
            }
        }
    }
}
```

### RESPONSE (GAGAL)

```json

```

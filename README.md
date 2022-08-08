##### Nama: Abdul Hamid
##### Kelas: XII RPL 1
##### No: 02

# MODUL 4

![183339403-810e381e-df7d-461a-8580-e3282bcf1c0f](https://user-images.githubusercontent.com/109930532/183356465-543f5129-60a7-4c5b-abbf-0e04544cd61f.png)

Selanjutnya kita akan membuat content yang akan menuju ke halaman barang dan kategori
Barang :
@extends('layout.App')

@section ('title')
    barang
@endsection

@section ('content')
<div class= 'mt-3'>
    <table class="table table-striped">
            <thead>
                <tr>
                    <th width="5%"> No.</th>
                    <th> Nama.</th>
                    <th width="15%"> Kategori.</th>
                    <th width="10%"> Qty.</th>
                    <th width="15%"> Harga Beli .</th>
                    <th width="15%"> Harga Jual .</th>

                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>1</td>
                    <td>Meja</td>
                    <td>ATK</td>
                    <td>1</td>
                    <td>50000</td>
                    <td>55000</td>
                    <td>Hapus | Edit</td>
                </tr>
            </tbody>
        </table>
</div>
@endsection 


![183339822-f03f24fc-2413-4d26-9351-a4d104cad483](https://user-images.githubusercontent.com/109930532/183356934-839ceb83-47df-48c9-a9cd-7b41c7629b8b.png)



 Kategori :
@extends('layout.App')

@section ('title')
    Kategori
@endsection

@section ('content')
<div class= 'mt-3'>
    <table class="table table-striped">
            <thead>
                <tr>
                    <th width="5%"> No.</th>
                    <th> Nama.</th>
                    <th width="15%"> Aksi.</th>
                    
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>1</td>
                    <td>ATK</td>
                    <td>Hapus | Edit </td>
                </tr>
            </tbody>
        </table>
</div>
@endsection 

![183339875-2cd3663d-2362-4c88-8f62-65d483ae103f](https://user-images.githubusercontent.com/109930532/183357496-9104aa13-ab9b-4e92-aea5-7678b1da8057.png)


Search dicrome/google
http://127.0.0.1:8000

![183340256-e7c27392-c538-4cd0-838e-0c73670e618d](https://user-images.githubusercontent.com/109930532/183357622-e815f3c5-cbf1-4370-a16c-5b57911c461b.png)


![183340339-acdb902a-5caa-4674-9c60-d16455db4e5c](https://user-images.githubusercontent.com/109930532/183357656-7b737c04-0021-4708-9296-e8b5885216c7.png)






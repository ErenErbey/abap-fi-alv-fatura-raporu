# ABAP - FI Müşteri Fatura Verileri Raporu

Bu projede SAP ABAP diliyle, SAP FI modülündeki müşteri fatura verileri hem klasik `WRITE` yöntemiyle hem de `ALV Grid` yapısı ile raporlanmıştır.  

## Özellikler
- `BKPF` ve `BSID_VIEW` tablolarından veriler JOIN ile çekilmektedir  
- `T003T` tablosundan belge türü açıklaması alınmakta  
- Kullanıcıdan belge numarası (belnr) alınarak veri filtrelenmektedir  
- Kullanıcı iki farklı çıktı türü arasında seçim yapabilmektedir:  
  - Klasik `WRITE` formatı  
  - `CL_SALV_TABLE` ile ALV Grid görünümü

## Kazanımlar
- ALV Grid kullanımı (`CL_SALV_TABLE`)
- Inner Join ile veri çekme  
- Seçim ekranı ve kullanıcı girişleri  
- SAP FI modülü tabanlı veri okuma
# abap-fi-alv-fatura-raporu

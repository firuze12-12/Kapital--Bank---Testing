## Bu Checklist Kapital Bank rəqəmsal bankçılıq sistemində **balance inquiry** funksiyasının düzgün işləməsini yoxlamaq üçün hazırlanmışdır .
## Preconditions
- [ ] Users systemə uğurla **login** olub
- [ ] User - in **active account** mövcuddur
- [ ] **Session** aktivdir

## Positive Checks
- [ ] Carı **balance** düzgün göstəriir
- [ ] **Currency** (AZN) düzgün əks olunur
- [ ] Balance real vaxtda yenilənir
- [ ] Bir neçə hesab olduqda düzgün hesab seçilir

## Negative Checklist
- [ ] Session bitdikdə balans göstərilmir
- [ ] **Sevrev Error** zamanı uyğun mesaj çıxır
- [ ] Hesab mövcud olmadıqda **error message** göstərilir

## Data Consistency
- [ ] Web və mobile platformalarda balance eynidir
- [ ] Transfer sonrası balance yenilənir
- [ ] Refresh etdikdə səhv məlumat göstərilmir

## Platform Checks
- [ ] Web aplication ( Chrome )
- [ ] Web aplication ( Firefox )
- [ ] Mobile application ( Android )
- [ ] Mobile application ( İOS )

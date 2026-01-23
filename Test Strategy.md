# Test Strategy -Kapital Bank Balace Module
## İntroduction
Bu sənəd Kapital Bank rəqəmsal bankçılıq sistemi üçün **test strategy** sənədidir.
Sənəd balans yoxlama funksiyası üçün ümumi test yanaşmasını təsvir edir .

## System Overview 
Test edilən sistem aşağıdakı komponentlərdən ibarətdir :
- Web application
- Mobile application ( Android , İOS )
- Backend API
- Database

## Test Scope

### İn Scope
Aşağıdakı funksionallıqlar test edilir :
- Balace inquiry
- UI validation
- API response validation
- Possitive və Negative scenario

## Test Types
Layihədə aşağıdakı **test types** istifadə olunur :
- Functional testing
- Positive testong
- Negative testing
- Regession testing

## Test Approach
Testlər əsasən **manual testing** üsulu ilə aparılır
API yoxlamaları üçün **Postman** alətindən istifadə olunur

## Entry Criteria
Test prosesinə başlamaq üçün :
- Login funksiyası işlək olmalıdır
- Test environment aktiv olmalıdır
Test data mövcud olmalıdır

## Exir Criteria
Test prosesi aşağıdakı hallarda tamamlanmış sayılır :
- Bütün balance testləri icra olunub
- Crictical bug mövcud deyil
- Test nəticələri sənədləşdirilib

## Risks 
- Yanlış balace göstərilməsi riski
- API response gecikməsi riski

## Tools
- Postman
- Chrome DevTools
- Github İssues

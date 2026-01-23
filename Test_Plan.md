# Test Plan - Balance İnquiry Module

## Test Plan Objekective
Bu test plan Kapital Bank balace yoxlama funksiyasının test edilməsi məqsədi ilə hazırlanmışdır .

Əsas məqsəd istifadəçiyə göstərilən balance məlumatının düzgünlüyünü yoxlamaqdır .


## Test Items
Testlər aşağıdakı mühitləedə aparılır :
- Browser : Chrome , Firefox
- Mobile OS : Android , İOS
- Database : QA database

## Test Desing Techiques
Test case-lər aşağıdakı **Test desing techniques** əsasında hazırlanır :
- Equivalence Partitioning
- Boundry Value Analysis
- Error Guessing

  ## Test Scenario

  ### Positive Scenario
  - User balans səhifəsinə daxil olur
  - Sistem düzgün balans göstərir
 
     ### Negative Scenario
    - Session expired vəziyyəti
    - Hesab mövcud deyil
   
       ## Test Execution
      Testlər checklist və manual test case-lər əsasında icra olunur
      Nəticələr test sənədlərində qeyd edilir

       ## Defect Reporting
      Tapılan bug-lar **Github İssues** üzərində qeyd olunur
      Bug repot-a severity və priority əlavə olunur

       ## Test Deliverables
      - Checklist
      - Test Plan
      - Test Strategy
      - Bug Reports

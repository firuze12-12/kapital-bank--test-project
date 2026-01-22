# Test Strategiyası - Kapital Bank

# Introductıon
Bu sənəd Kapital Bank layihəsi üçün test strategiyasını təqdim edir .Test strategiyası layihə boyu tətbiq ediləcək test yanaşmasını , test növlərini ,riskləri və istifadə ediləcək alətləri təsvir edir.Funksiyaların düzgün işləməsi , test planın hazırlanması, sistemin Web , mobile və backend hissələrini əhatə edir . 
# Test Scope
## İn Scope
## Aşağıdakı funksionallıqlar test ediləcək :
- Login və Autehtication
- Account Balace İnquiry
- Money transfer ( daxili köçürmələr )
- error handing və Validation
- Web / Mobile tətbiq
- Backend API
- Database
##  Out of Scopa
- Load və Stress testing
- Penetration testing
- Production mühitində tetlər
# Test types
## Layihədə aşağıdakı test növləri tətbiq ediləcək
- Funksional Testing ( Əsas biznes funksiyalarının yoxlanması )
- Boundary Value Testing ( limit dəyərlərinin yoxlanması )
- Regression Testing ( dəyişikliklərdən sonra əsas funksiyaların təkrar yoxlanması )
- Positive Testing ( düzgün məlumatlarla sistem davranışı )
- Negative Testing ( yanlış və boş məlumatlarla testlər )
  # Test Apporch
  Testlər manual şəkildə aparılacaq
  Manual testing seçilmə səbəbi
  - Funksionallıqların tez- tez dəyişməsi
  API səviyyəsində ilkin yoxlamalar Postman vasitəsilə aparılacaq
# Entry Criteriya
## Test prosesinin başlanması üçün aşağıdakı şərtlər ödənməlidir :
- Tələblər ( requierements ) təsdiqlənmiş olmalıdır
- Test mühiti ( QA environment ) hazır olmalıdır
- Build deploy edilmiş olmalıdır
- Test datası mövcud olmalıdır
- Kritik blocker bug mövcud olmamalıdır
# Exit Criteriya
## Test prosesi aşağıdakı hallarda tamamlanmış sayılır
- Planlaşdırılmış testlərin 95 %-i icra olunub
- Kritik və yüksək prioritetli bug-lar bağlanıb
- Test nəticələri sənədləşdirilib
- Test Summary Report hazırlanıb
# Risks
## Functional risk
- Money transfer zamanı yanlış balans hesablanması
- Mitigation: Hesablama ssenarilərinin geşiş test edilməsi
# Security Risks
- Yanlış login cəhdlərinin limitlənməsi
# Environment Risks
- Test və prod mühit fərqləri
# Tools
- Postman - API testlər
- Chrome Devtools - UI və network analiz
- Github İssues - Bug tracking
- Android Emulator / İOS Simulator - Mobil testlər



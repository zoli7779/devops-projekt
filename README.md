# DevOps Projektfeladat - Minimális CI/CD Pipeline

Ez a projekt egy minimális CI/CD folyamatot demonstrál egy egyszerű Python Flask alkalmazáson keresztül, GitHub Actions és Docker használatával.

## Funkciók
- **Alkalmazás:** Python Flask alapú JSON API (`/` és `/health` végpontokkal).
- **Tesztelés:** Automatikus egységtesztek a `pytest` keretrendszerrel.
- **Konténerizáció:** Docker image építés és lokális tesztelés a pipeline-ban.
- **CI/CD:** GitHub Actions alapú automatizált build, teszt és deploy folyamat.
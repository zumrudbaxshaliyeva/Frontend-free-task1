# Tələbələr üçün GitHub Talimatları

## 1. Layihə Qovluq Strukturu
Layihənizin qovluq strukturu aşağıdakı kimi olmalıdır:

```
project-folder/
├── index.html
├── assets/
│   ├── img/
│   │   └── example.png
├── README.md
```

### İzah:
- **index.html**: Layihənin əsas HTML faylı. Bu fayl şəkil, mətn və mətn başlığını ehtiva edir.
- **assets/**: Layihəyə aid resursların saxlanıldığı qovluq.
  - **img/**: Şəkillər üçün qovluq.
- **README.md**: Layihəniz haqqında məlumatların yer aldığı fayl.

## 2. Öz Branch-ınızı Yaratmaq və GitHub-a Yükləmək
Aşağıdakı addımları izləyin:

### Addım 1: Repositoriyanı klonlayın
```bash
git clone <repository-link>
cd <repository-name>
```

### Addım 2: Yeni branch yaradın
```bash
git checkout -b <branch-adı>
```

### Addım 3: Fayllarınızı əlavə edin və commit edin
```bash
git add .
git commit -m "Fayllar əlavə olundu"
```

### Addım 4: Branch-ınızı GitHub-a göndərin
```bash
git push origin <branch-adı>
```

## 3. README.md Faylı Şablonu
Aşağıda README.md faylı üçün bir şablon verilmişdir:

```markdown
# Layihə Adı

## Layihə Haqqında
Bu layihə şəkil, mətn və mətn başlığından ibarətdir.

## Layihə Qovluq Strukturu
```
project-folder/
├── index.html
├── assets/
│   ├── img/
│   │   └── example.png
├── README.md
```

## Şəkil Nümunəsi
Layihədə istifadə olunan bir şəkil nümunəsi:

![Example Image](assets/img/example.png)

## Layihəyə Necə Başlamaq Olar
1. Repositoriyanı klonlayın:
    ```bash
    git clone <repository-link>
    ```
2. Qovluğa keçin və faylları yoxlayın.

## Keçid Linki
Layihəni canlı olaraq bu linkdən görə bilərsiniz: [Layihə Linki](https://ornek-link.com)

---

Hazırlayan: [Adınız]

# Star Wars Snakemake Workflow

## Описание

Простой workflow на **Snakemake**, который демонстрирует автоматизацию процессов.
В нашем примере workflow запускает Python-скрипт, который генерирует список персонажей **Star Wars** и подсчитывает их количество.

Цель — показать работу Snakemake, управление зависимостями и воспроизводимость результатов.

---

## Установка и запуск проекта

### 1. Клонируем репозиторий

```powershell
git clone https://github.com/Danilkynev/danil-kynev-hw/tree/hw1
cd danil-kynev-hw
```

### 2. Создать виртуальное окружение

```powershell
python -m venv venv
```

### 3. Активировать окружение

```powershell
# PowerShell
.\venv\Scripts\Activate.ps1
```

### 4. Установить Snakemake

```powershell
pip install snakemake
```

### 5. Запуск workflow

```powershell
snakemake
```

* Snakemake создаст файл `result.txt` в корне проекта
* Файл содержит список персонажей и их количество
* Вывод, который вы должны получить:

```
Star Wars characters:
- Luke Skywalker
- Leia Organa
- Darth Vader
- Yoda
- Obi-Wan Kenobi

Total characters: 5
```

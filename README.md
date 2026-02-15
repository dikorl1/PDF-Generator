# PDF-Generator
Автоматический генератор PDF-чеков/отчётов из CSV/JSON по HTML-шаблонам (CLI Python)
Готовое решение для создания профессиональных PDF-инвойсов: загружаете данные в CSV → выбираете шаблон → получаете PDF с кириллицей (ReportLab). Работает оффлайн на Windows/macOS.

✨ Возможности:

CLI-меню: выбор CSV/JSON + шаблона + записи

2 responsive HTML-шаблона (синий отчёт, зелёный чек)

Поддержка кириллицы (Arial/DejaVuSans)

Автооткрытие PDF в браузере

Тестовый CSV с 5 компаниями
Образцы чеков:
[invoice_2.pdf](https://github.com/user-attachments/files/25325073/invoice_2.pdf)
[invoice_4.pdf](https://github.com/user-attachments/files/25325072/invoice_4.pdf)


🚀 Быстрый старт:

pip install -r requirements.txt
python generate_pdf.py
📁 Файлы: generate_pdf.py | template.html | template2.html | companies.csv | requirements.txt | README

### Лабораторная работа №6 по DevOps
Описание файлов:

- inventory.ini -- инвентарь, где прописываем хост второй ВМ
- playbook.yml -- плейбук, который использует роль nginx-vhosts
- roles/nginx-vhosts/tasks/main.yml -- здесь прописаны задачи по установке nginx, копированию конфигов и стартовых страниц, 
- roles/nginx-vhosts/handlers/main.yml -- хэндлер для перезапуска nginx
- roles/nginx-vhosts/templates/index.html.j2 -- шаблон сайта
- roles/nginx-vhosts/templates/site.conf.j2 -- шаблон конфига сайта
- run_playbook.sh -- bash-скрипт для запуска плейбука
- выполнение bash-скрипта.png -- скриншот с результатом выполнения bash-скрипта
- проверка в консоли.png -- скриншот проверки сайтов в терминале
- проверка в браузере.png -- скриншот проверки сайтов в браузере (вместе с файлом hosts)

- .github/workflows/devops_course_pipeline.yml -- тестовый пайплайн для github actions
- .github/workflows/lint.yml -- пайплайн c линтером для проверки кода
- workflows.png -- скриншот с рабочими процессами
- first-job.png -- скришот работы тестового пайплайна
- lint.png -- скришот работы линтера

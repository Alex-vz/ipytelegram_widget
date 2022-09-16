# How to install and build

Создаем шаблон проекта:

	cookiecutter https://github.com/jupyter-widgets/widget-cookiecutter

Переходим в созданный каталог.

Инициализируем git репо. В т.ч. что бы следить за изменениями

	git init
	git add -A
	git commit -m "Initial"

Устанавливаем новое расширение в Python, вариант для разработки

	python -m pip install -e .



	cd js
	jlpm install
	jlpm run build

Устанавливаем расширение для Jupyter Lab

Переходим в корень проекта.

	jupyter labextension develop . --overwrite

Проба:

Запускаем Jupyter Lab

```python
import ipytelegram_widget
w = ipytelegram_widget.HelloWorld()
w
```


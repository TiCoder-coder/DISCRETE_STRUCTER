web: cd Graph_visualizer
web: gunicorn Graph_visualizer.wsgi:application --bind 0.0.0.0:$PORT
web: python manage.py migrate && gunicorn Graph_visualizer.wsgi
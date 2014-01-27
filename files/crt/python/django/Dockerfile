FROM mattdm/fedora

{{ setup_command }}
ADD . /srv/{{ basename }}
EXPOSE 8000
CMD /srv/{{ basename }}/manage.py runserver

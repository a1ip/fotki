#Fotki
*NodeJs api ��� ������ � �������� [������.�����](https://tech.yandex.ru/fotki/).* 
##Api
*��������� �������� ������� ��. � jsDoc*
###�����������
````fotki.auth('username', 'OAuth token');````

[���������� ����� ����� �������� �������](https://tech.yandex.ru/oauth/doc/dg/tasks/get-oauth-token-docpage/)
###��������� ���������� ��������� 
````fotki.getServiceDocument()````
###�������� � ���������
````fotki.albums.xxx````
###�������� � �������������
````fotki.photos.xxx````
###�������/��������
````fotki.helpers.xxx````
##�������
###�������� �������
````
fotki
    .auth('username', 'OAuth token')
    create({ title : 'Example album', summary : 'Album description', password : '' });
````
###�������� ����������� � ������
````````

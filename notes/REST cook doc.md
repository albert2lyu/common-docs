

## tips

### RESTful API��������ʵ����������

https://segmentfault.com/q/1010000001616176

https://www.npmjs.org/package/restful-api

```
POST /posts/batch
     Body: { 'delete': [1, 2, 3, 4, 5, 10, 42, 68, 99] }
```

http://backbonejs.org/#FAQ-tim-toady

```json
  {
    "create":  [array of models to create]
    "update":  [array of models to update]
    "destroy": [array of model ids to destroy]
  }
```

https://segmentfault.com/q/1010000004407452

��һЩ���������delete����body���͵ģ���������԰����е�IDsһ�ηŽ�ȥȻ����DELETE ���� ����һ��д���Ƿֳ�2����ɣ���һ������POST���󣬼�������Ҫɾ����IDsȻ�󷵻�һ��header,Ȼ�����������header����DELETE���󡣾��岽������:

```
����POST���󣬼������е�IDs (���Դ浽Redis������ͨ���ݿ�)
http://example.com/posts/deletes

�ɹ�����Է���һ��Ψһ��ͷ�ļ���

HTTP/1.1 201 created, and a Location header to:
http://example.com/posts/deletes/KJHJS675

Ȼ���������Ajaxֱ�ӷ���DELETE����:
DELETE http://example.com/posts/deletes/KJHJS675

�����Ϳ����ڲ���¶IDs������¸��Ӱ�ȫ��ɾ�������Ŀ��
```

��������`DELETE` id���顣

�������ۣ�

https://www.v2ex.com/t/154258


����ע�����cloudflare�˺�
--------------------------

python3 д��һ������ע��cloudflare�˺ŵĽű�

`bulk_cf_account.py` ����ע���˺�
`cloudflare.py` ���������˺�

## ��Ҫ��װ�İ���

* requests
* names

## bulk_cf_account.py ������Ҫ�޸ĵ�����

```python
DOMAINS = [] # �����Ҫ��Ŀǰ���õ�������Խ��Խ�ã�20���㹻�� 
SAVE_FILE = 'cf_accounts_by_lanthy_at_20171207.txt' # ������ļ������Լ����� 
HTTP_PROXY="http://192.168.10.220:1080" #��Ҫʹ�õĴ�������� 
```

## ������ļ�����������Tab�ָ��ģ����Ե��뵽excel��

`���䣬���룬name_servers��api_key��id��username��created_on`

��װ����
========

1. ����pyhton3��װ����װ�����а�python���뵽����������
2. ��װpip
  ���� https://raw.github.com/pypa/pip/master/contrib/get-pip.py 
  Ȼ�������������� (��Ҫ����ԱȨ��): 
  `python get-pip.py` 
3. ��װ��
  pip install requests names



# Trojanɵ��һ���棬û������Ҳ���Բ���ѧϰ

	bash <(curl -L -s https://git.io/trojan.sh)

### ���� trojan windows �ͻ���

- https://github.com/trojan-gfw/trojan/releases/download/v1.13.0/trojan-1.13.0-win.zip

- Windows����Ҫ��װ vc_redist.x64.exe (Visual C++ Redistributable for VS 2015)

- https://aka.ms/vs/16/release/vc_redist.x64.exe

#### �༭ ���ؿͻ��� config.json �ļ�

- example.com �ĳ� ssl.srgb.work ; ���޸� trojan ��֤����

### Chrome ��������ã�ʹ��SwitchyOmega���������ͬSS��Brook

- ����Э�� SOCKS5 ��������� 127.0.0.1 ����˿� 1080


### �༭�������������ļ�

- C:\Windows\System32\drivers\etc\hosts

### ��ӱ����������� (��ʵ��IP�޸�)

	188.188.188.188  ssl.srgb.work

----------

## ��������Լ�������֤�飬�滻��Կ����������
- ��Կ: /var/certificate.crt
- ˽Կ: /var/private.key
```
# ���� trojan
systemctl restart trojan

# �鿴 trojan
systemctl status trojan
```

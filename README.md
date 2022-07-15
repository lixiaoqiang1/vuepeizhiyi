<p align="center">
  <img width="200" src="./docs/images/udesk.png">
  <h2 style="width:100%; text-align:center;"">UDesk Mobile Template</h2>
</p>


## ���

ͳһ�ͻ���Ӧ��ƽ̨(UDesk) for Mobile ģ�幤��(**udesk-mobile-template**)���� UDesk �ƶ� H5 ��ܹ�������һ��ʹ�� Vue ����ջ(vue��vue-router��vuex)ʵ�ֵĵ�ҳӦ�ã������˶�̬·�ɡ�״̬����Ȩ����֤���첽����ǰ������ģ��(Mock)�����Ի����õȵ�ҳӦ�ñ���ģ�飬�����򵥵�ҳ�沼�ֺ�ҳǩ�������ʺ�������ҵ���к�̨��Ʒ����ʽ�з���

����ͽ�������ѧϰ��ʹ�� UDesk for Mobile ���幤��(udesk-mobile-boilerplate)��

- **UDesk for Mobile ��������**��[����Ԥ��](http://dev.udesk.abc/mobile-boilerplate/)
- **UDesk for Mobile ģ�幤��**��[����Ԥ��](http://dev.udesk.abc/mobile-template/)

ͳһ�ͻ���Ӧ��ƽ̨(UDesk)�ƶ� H5 ��ܣ����� Vue ����ջ�ṩ���п�ܡ�UI ����⡢������̡�ģ�幤�̡����幤�̡��������ߣ����ּܹ��ߣ��ȹ���ģ�飬��������ͨ���ƶ��� H5 �������ʵ�Ӧ��ϵͳ��֧�ֶ������������ UC �ȣ���΢�������������UMAP Ӧ����Ƕ WebView �����������

### �ĵ�

- �����ĵ�������� [����](http://dt.abc/)
- �����ĵ�����������̸�·���µ� docs Ŀ¼ 

## ��

### ����ʹ��

����ϵ����Ӧ��ƽ̨�з��� UDesk ��Ŀ�����빤�̴��롣

### ��������

�ڰ�װ��Ŀ����֮ǰ�����뱣֤���ذ�װ�� Node ��������

#### ��װ NodeJS �� NPM

NodeJS ��һ������ Chrome V8 ����� JavaScript ���л�����
NodeJS �ٷ���ַ��https://nodejs.org/

�������أ�node-10.15.3�����°棬64λ��Windows ƽ̨��
����ȶ������� node-v10.15.3-x64.msi �ļ�����˫�����ļ����а�װ��
ע������ NodeJS �Ѱ��� NPM�������ٰ�װ NPM��
��װ��ɺ����������������룺

```bash
node -v
npm -v
```

����ʾδ�ҵ�������鰲װ·���Ƿ��Ѽ��뱾��ϵͳ`Path`������

```bash
# ����Ĭ��Դ
npm config set registry=http://zpk.abc/artifactory/api/npm/npm-test/

# ��װ NPM Դ������
npm install nrm -g

# ��� ZPK ���ÿ�Դ
nrm add zpk-test http://zpk.abc/artifactory/api/npm/npm-test/ 

# ��� ZPK ������Դ
nrm add zpk http://zpk.abc/artifactory/api/npm/npm/ 

# �г�Դ�б�
nrm ls

# ����Դ�����ٶ�
nrm test 

# ʹ��ָ��Դ���Ƽ�ʹ�� ZPK ���ÿ⣩
nrm use zpk-test
```

#### ��װ Python

Python ��һ�ָ߲�εĽ���˽����ԡ������ԡ������Ժ��������Ľű����ԡ�

python ������ַ��http://www.python.org

�������أ�python-2.7.16 �� 2.x �����°棬64 λ��Windows ƽ̨��
Windows �汾����֮�󣬻�õ�һ����װ����ֱ�ӵ����װ��
��������ִ�У�

```bash
python -v
```

�ɲ鿴 Python �汾������ʾδ�ҵ�������鰲װ·���Ƿ��Ѽ��뱾��ϵͳ Path ������


#### ��װ node-sass

��������ԭ��UDesk ��������/ģ�幤�������� node-sass ģ���޷�ֱ�Ӵ� NPM Դ��ȡ����Ҫָ����װλ��Ϊ�����ļ���

- 1. ��ȡ node-sass �� .node �ļ�

node-sass �� .node �ļ��ɴ�github��ȡ��[��ȡ��ַ](https://github.com/sass/node-sass/releases) 
���������أ�node-sass-4.11.0�����°棬64λ��Win32ƽ̨��NODE_MODULE_VERSION 64����

- 2. ���� node-sass �ı���·��

��ȡ��.node�ļ���win32-x64-64_binding.node���󣬽�����ڱ����Զ���Ŀ¼��Ȼ��������������ִ���������ע����������Ϊ�Զ����Ŀ¼·��������ΪӢ�İ�ǣ���

```bash
npm config set sass_binary_path {�Զ���·��}\win32-x64-64_binding.node
npm config set sass_binary_site {�Զ���·��}\win32-x64-64_binding.node
```

ִ����������鿴���ú�Ľ����

```bash
npm config get sass_binary_path
npm config get sass_binary_site
```

### ��װ����

```bash
# ���빤��Ŀ¼
cd udesk-mobile-template
```

**�ر�˵��**
���ڵ�ǰ���� NPM Դ���ȶ���������������`npm install`���ֱ����ϵ����Ӧ��ƽ̨�з��� UDesk ��Ŀ���ȡ���� NPM ������`udesk-mobile-template_v5.1.0_node_modules.zip`����zip�е� node_modules Ŀ¼��ѹ�������̸�Ŀ¼�£�Ȼ��ֱ��ִ��`npm run dev`�����������̡�

```bash
# ��װ���������ѻ�ȡ node_modules Ŀ¼�򲻱�ִ�д�����
npm install
```

### ��������

```bash
npm run dev
```

�����ɹ��󣬽��Զ���������� http://localhost:9527 ҳ�档

### ����

```bash
# �������Ի���
npm run build:stage

# ������������
npm run build:prod

# ����һ������������������ .war ��
npm run package
```

### ��������������

���[��������������]()

### �����֧��

���[IE�����Ը���]()

### ����

```bash
# Ԥ����������Ч��
npm run preview

# Ԥ����������Ч�� + ��̬��Դ����
npm run preview -- --report

# �����ʽ���
npm run lint

# �����ʽ��鲢�Զ��޸�
npm run lint -- --fix
```

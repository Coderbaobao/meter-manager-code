# ����ϵͳ

## �汾˵��

### Version 1.0.0

## ������������˵��&����˵��

| ��� | ��Ŀ | ���� | �汾 | �˿ڷ��� | ����˵�� |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 1 | cmcciot-meter-registry-microservice | ����ע������ | 1.0.0 | 8501 | 159 server,160 server |
| 2 | cmcciot-meter-gateway-microservice | ·������ | 1.0.0 | 8502 | 159 server��160 server |
| 3 | cmcciot-meter-auth-microservice | Ȩ����֤΢���� | 1.0.0 | 8503 | 159 server��160 server |
| 4 | cmcciot-meter-fee-microservice | ���ù���΢���� | 1.0.0 | 8504 | 159 server��160 server |
| 5 | cmcciot-meter-admin-microservice | ��̨����΢���� | 1.0.0 | 8505 | 159 server��160 server |
| 6 | cmcciot-meter-dataanalysis-microservice | ����ϴ�΢���� | 1.0.0 | 8506 | 159 server,160 server |
| 7 | cmcciot-meter-report-microservice | ����΢���� | 1.0.0 | 8507 | 159 server��160 server |

##���ػ���˵��

| ��� | ��Ŀ | ���� | �汾 | �˿ڷ��� | ����˵�� |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 1 | cmcciot-meter-registry-microservice | ����ע������ | 1.0.0 | 8761 | localhost |
| 2 | ***cmcciot-meter-gateway-microservice����ʱ���ɵ�auth��ȥ��*** | ·������ | 1.0.0 | 8502 | 159 server��160 server |
| 3 | cmcciot-meter-auth-microservice | ·�����أ�Ȩ����֤΢���� | 1.0.0 | 8763 | 159 server��160 server |
| 4 | cmcciot-meter-fee-microservice | ���ù���΢���� | 1.0.0 | 8764 | 159 server��160 server |
| 5 | cmcciot-meter-admin-microservice | ��̨����΢���� | 1.0.0 | 8765 | 159 server��160 server |
| 6 | cmcciot-meter-dataanalysis-microservice | ����ϴ�΢���� | 1.0.0 | 8766 | 159 server,160 server |
| 7 | cmcciot-meter-report-microservice | ����΢���� | 1.0.0 | 8767 | 159 server��160 server |

## ����˵��
1. registryע�����ģ�����ʵ��������ʱ�е�ע����������
2. auth��·�������Լ�Ȩ�޿���΢����, ·��ǰ׺ /auth/**
3. admin��̨����΢���񣺱�ƣ�ϵͳ���õ�ģ�������� ·��ǰ׺ /**
3. fee���ù���΢���񣺷��ù���ģ�飬��Ҫ������΢������н���,·��ǰ׺/fee/**
4. datanaalysis����΢���񣺳���ͳ�ƣ���Ҫ����ù���΢����,·��ǰ׺ /record/**
5. reprot����΢���񣺱���ͳ��ģ����룬·��ǰ׺ /report/**
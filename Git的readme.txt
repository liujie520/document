git init:��ʼ���ֿ�

1��Git��װ֮����Ҫ����һЩ������Ϣ����

����a�������û�����git  config -- global  user.name  '����github��ע����û���';

����b�������û����䣺git  config --global  user.email  'ע��ʱ�������';


2:��ӵ��ֿ�
git add index.html(cmd����,Ҫ��index.html��Ŀ¼��)
git add *.html �����һ���ļ���
git add . (��������ļ�)


3���鿴
git status

4:ɾ��
git rm --cached  �ļ���

5���ύ
git commit(֮����Ҫ���뱸ע��Ϣ)
��Ҳ����(�������ύҲ��ע����Ϣ)
git commit -m '�ڴ����뱸ע��Ϣ'


6:��֧
������֧: git branch ��֧����
�л���֧: git checkout ��֧����
masterΪ����֧
����ֻ��һ��,����֧�кܶ�,
���ֻ��Ҫ����֧�����ݺϲ��������о�ok
�ϲ���֧: git merge ��֧���֣�ֻ�������������˲�����


7:���͵�Զ�ֿ̲�
git remote add origin https://github.com/liujie520/homework.git
��
 git push -u origin master

8����������������ص�����
git clone https://github.com/liujie520/homework.git(�ò������뵽�ļ����в�������)

�����¡֮��,�ļ�����ֻ������֧�Ķ���
������뿴��֧��Ķ���,��ô�͵���cmd��������ļ�����ȥ�л���֧
�л���֮��,���ܿ���������֧��������

tip:
�����ϴ�����ļ�,���Լ����޸���,������Ҫʹ��
git addȻ����
git commit -m �����ύ

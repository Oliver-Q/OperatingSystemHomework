1������3.3.2 ��thread_huchi.c ��Դ���������write �̺߳�read �߳��Ƿ�Ӧ��������ӡ�����߳�ÿ�δ�ӡ
һ�У�ʵ�����н���Ƿ���������������ǣ����������ԭ��
���н��ֻ��write��ӡ��䣬write��whileѭ����sem_post(&sem);����൱��V�������ͷ�sem�ź�����Դ�Ӷ�����ѭ��

2�� ���޸�thread_huchi.c, ʵ��write �̺߳�read �̵߳�ͬ�����Ӷ�ʵ��������ӡһ�е�Ч����
ɾȥwrite�е�sem_post(&sem);��read�е�sem_wait(&sem);�������11410441-sem_huchi.c
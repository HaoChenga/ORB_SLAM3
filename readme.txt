
ORB_SLAM3 windows�±���˵��

����vs2019���룬vs2017����Ҳ���ԡ�vs2015��������ҳ���

1. ����boost��
�������أ� https://www.boost.org/users/download/
https://sourceforge.net/projects/boost/files/boost-binaries/
�����ص��� boost_1_74_0-msvc-14.2-64.exe��˫����ѹ�õ�boost_1_74_0Ŀ¼��

2. ��ѹ�ֵ� 
ocabulary\ORBvoc.txt.tar.gz
��ѹ����ǰĿ¼��

3. buildvs19 �´�ORM_SLAM3.sln��ֱ�ӱ��뼴�����С�
������mono_kitti���������Գ���Ҳ�����ԣ�ֻ��Ҫ�Ѱ���Ŀ¼����Ŀ¼��������������mono_kitti��ͬ���ɡ�
mono_kitti ���е�������ʾ����
..\..\..\Vocabulary\ORBvoc.txt ..\..\..\Examples\Monocular\KITTI00-02.yaml F:\data\kitti\dataset\sequences\00

��������Щ�����Ѿ�����ã���ֱ��ʹ�ã��㲻��Ҫ��ͷ���룩
������룺
1. ����Thirdparty/DBoW2
��cmake�������̣��򿪹��̣�boostĿ¼���뵽DBoW2���Ӱ���Ŀ¼�����뼴�ɡ�

2. ���� Thirdparty/g2o
g2oĿ¼�µ��п��ܻ��������Ҽ��˸��汾 g2o_win��
����ֱ�Ӵ� g2o_win\buildvs15 �µĹ��̱��롣
�����Ҽ����ԣ�C/C++������ѡ����ϸ���ѡ�� /bigobj �������е����ÿո������
������ʱ���е㳤���ҰѶദ����������Ϊ�񣬷�ֹ������

3. ����ORM_SLAM3
�Ұ�cmakelist.txt ��opencv��eigen�ȵ�����ȥ���ˣ�����vs����֮��Ҫ�ֶ��ӵ����Ӱ���Ŀ¼��
ǰ��boost��Ŀ¼ҲҪ���ϣ�pangolin��Ŀ¼Ҳ���ϡ�
��Ҫ�õ�glew���������أ�ThirdpartyĿ¼���Ѱ�����
�ദ��������������ռ���ڴ��ǳ���



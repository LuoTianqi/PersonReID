##################################################################
# 1. ���뵥��ͼƬ�����top15��ͼƬ
run:
python test_single.py --pic_path (path of a single picture)

example:
python test_single.py --pic_path dataset/test_query/-1/015995.jpg

��result_JPG�ļ�����鿴���ɽ��
'0_xxx.jpg'��queryԭͼ
'1_xxx.jpg'~'15_xxx.jpg'��Top15�Ľ��

##################################################################
# 2. ����query���ݼ������xml�ļ�
run:
python test_multiple.py --query_dir (path of query dataset)

example:
python test_multiple.py --query_dir dataset/test_query

��result_XML�ļ�����鿴���ɽ��



# netty-introduction-demo  
Netty������ʵ��

���������е�һ��Netty�Ŀͻ��˺ͷ�����
����ECHOЭ�飬Ҳ���ǿͻ�������ʲô���������ͷ���ʲô��

ChannelOption.SO_BACKLOG:   
��������TCP�ں�ά����������A��B  
�ͻ�������������connectʱ, ����SYN(��һ������)  
������յ�SYN��, ��ͻ��˷���SYN ACK(�ڶ�������),  TCP�ں˽����ӷ������A  
�ͻ����յ��������˷���ACK(����������),  TCP�ں˽����Ӵ�A->B, accept����, �������  
A/B���еĳ��Ⱥͼ�ΪBACKLOG, ��accept�ٶȸ����ϣ�Ҳ����ͬʱ���ֹ��ࣩ, A/B����ʹ��BACKLOG����, �ͻ������ӾͻᱻTCP�ں˾ܾ�  
���Ե���SO_BACKLOG������һ����.Ĭ��ֵΪ50.  





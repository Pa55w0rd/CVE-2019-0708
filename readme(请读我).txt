һ. ����˵��

0708detector.exe��������360��˾��360Vulcan Team������һ����Ա��ΪCVE-2019-0708��WindowsԶ������Э��©���ļ�����,ԭ���ϸ�ɨ����򲻻����Ŀ��ϵͳ��������,�������Ժ���ʹ�á�

Ŀǰ����ֻ֧�ֵ���IP��ɨ��,���������й��������ɨ��ĳ���лл��

ע�⣺
1. ʹ��ǰ��������ںϷ���Ȩ����¶�Ŀ��ϵͳ����ɨ�裻
2. ʹ��ǰ����ע������������ǩ���Ƿ�Ϸ���
3. ������������������⵼�¼�ⲻ�ɹ���
4. ����и�������⣬���ʼ��ظ�����cert@360.cn 

��. ʹ�÷���

1. �򿪡������С������롡cmd.exe �����س�������

2. ��ת����������Ŀ¼�����絽C��detectorĿ¼��

c:\>cd c:\detector\

3. �� cmd.exe �����У�������Ĳ�������

c:\detector>0708detector.exe -t 192.168.91.138(Ҫ���Ե�Ŀ��IP) -p 3389(Ŀ��˿ڣ�һ�㶼��3389)

a) ��Ŀ�����©��

CVE-2019-0708 Remote Detection tool
                     by: 360Vulcan Team

[+] Connecting to RDP server.
[+] Socket : could not find a selected socket
[+] Establish connection with RDP server successful.
[+] Start 2nd stage detection.
[+] Connecting to RDP server.
[+] Establish connection with RDP server successful.
[!] !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
[!] !!!!!!WARNING: SERVER IS VULNERABLE!!!!!!!
[!] !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

b) ��Ŀ��ϵͳ�Ѿ�����NLA

CVE-2019-0708 Remote Detection tool
                     by: 360Vulcan Team

[+] Connecting to RDP server.
[!] Socket : recv error with -1 return
[!] Recv server TPDU req Failed
[*] Detect NLA enable! Server likely NOT vulnerable

c) ��Ŀ��ϵͳ�Ѿ����в����޸�

CVE-2019-0708 Remote Detection tool
                     by: 360Vulcan Team

[+] Connecting to RDP server.
[+] Establish connection with RDP server successful.
[+] Start 2nd stage detection.
[+] Connecting to RDP server.
[+] Establish connection with RDP server successful.
[*] Server likely NOT vulnerable


��. �޸�����

1. �������û�ǰ��http://dl.360safe.com/leakfixer/360SysVulTerminator_CVE-2019-0708.exe������ʹ��360Զ���������©�����߹��ߣ��޸�©���������û�ϵͳ�����ݰ�ȫ��

2. �������ض�Ӧ�İ�ȫ�������в������²���


��. ����У����

MD5:
febc027cee2782dba25b628ce3a893d6 *0708detector.exe

SHA256:
ccea8afec177d15d78329770b29f361b876addaa19eb93cabfaf90b896e03827 *0708detector.exe


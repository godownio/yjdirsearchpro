Program:
     yjdirscan(����Ŀ¼ɨ��רҵ��v1.1 Date:20201018)

Usage:
     -url https://www.demo.com
     -url https://www.demo.com -method GET -diy404 off -skipword not found   explain:use skip word mode(����:���ùؼ�������ģʽ)
     -fuzz https://www.demo.com/*/ -range 1,3
     -fuzz https://www.demo.com/admin/*.zip -range 3,3

Options:
     -check     Check Url State Failed Three Exit Scan,Default on/off
     -spider    Home Page Spider,Default on/off
     -diy404    Auto Filter Diy404(False200),Default on/off
     -method    HEAD or GET,Default HEAD
     -thread    1-100,Default 16
     -timeout   1000-60000,Default 6000
     -maxspeed  1-3000,Default 200
     -codes     httpcode,Default 200,301,302,304,403
     -files     all or xxx.txt,Default bak.txt,dir.txt
     -key       fuzz mode,Default abcdefghijklmnopqrstuvwxyz
     -range     fuzz mode,Default 1,3
     -save      Save to xxx.txt File,Default Not Save
     -skipsize  Skip Page size-size,Default Not use
     -skipword  method is GET and diy404 is off use,Default not found

Dicvar(bak.txt):
     www.demo.com  Split(3)  www=%a% demo=%b% com=%c%
         demo.com  Split(2)          demo=%b% com=%c%

ע�⣺����Զ�ģʽʲô��ɨ�費������ʱ�򣬿��Գ���һ���ֶ�����ģʽ/�Զ������ģʽ��GET+�ر��Զ���404���ˣ�
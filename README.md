# �ٷ��ĵ�ͬ����ʶ

 - Version: v0.6.11
 - Commit hash: 7343f8e776146bf4461348a9130f2c5040a0dfa0
 - Date: 2012/2/10 13:58:58

# ����Ŀ¼�ͷ������

* [ժҪ](./blob/master/api/synopsis_cn.markdown)
* [ȫ�ֶ���](blob/master/api/globals_cn.markdown)
* [��׼���������console��](blob/master/api/stdio_cn.markdown)
* [��ʱ��](blob/master/api/timers_cn.markdown)
* [ģ��](blob/master/api/modules_cn.markdown)
* [C/C++ ��չ](blob/master/api/addons_cn.markdown)
* [���̶���process��](blob/master/api/process_cn.markdown)
* [���ù��ߣ�util��](blob/master/api/util_cn.markdown)
* [�¼�ģ�飨events��](blob/master/api/events_cn.markdown)
* [�������ࣨBuffer��](blob/master/api/buffer_cn.markdown)
* ���ӿڣ�Stream��
* ����ģ�飨crypto��
* ��ȫ����Э�飨tls/ssl��
* �ַ�������
* �ļ�ϵͳ��fs��
* ·��ģ�飨path��
* ����ģ�飨net��
* ���ݱ���Э�飨udp/dgram��
* ��������dns��
* ���ı�����Э�飨http��
* ��ȫ���ı�����Э�飨https��
* ��ַ����ģ�飨url��
* ��ѯ������ģ�飨querystring��
* �ж�ȡģ�飨readline��
* ����ʽ�����У�repl��
* �������ģ�飨vm��
* �ӽ���ģ�飨child_process��
* ����ģ�飨assert��
* �ն�ģ�飨tty��
* ����ѹ������zlib��
* ����ϵͳģ�飨os��
* ����������debugger��
* ���ģ�飨cluster��
* ��¼
  * ��¼ 1: ������ģ���Ƽ�

# ��������

##addons_cn

 - Addon patterns�Ƿ���Ӣ��ԭ�ģ�line 80��

##module_cn

 - ����`module.require`������(line 385)

>Note that in order to do this, you must get a reference to the `module`
>object.  Since `require()` returns the `exports`, and the `module` is
>typically *only* available within a specific module's code, it must be
>explicitly exported in order to be used.

>ע�⣬Ϊ��ʹ��require�����������Ȼ�ö�`module`��������á���Ϊ`require()`�᷵��`exports`��
>����`module`ͨ��ֻ�������ģ���������Ч������ֻ����Ҫ�õ�ʱ�ŵ�����

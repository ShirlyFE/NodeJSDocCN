# �ٷ��ĵ�ͬ����ʶ

 - Version: v0.6.11
 - Commit hash: 7343f8e776146bf4461348a9130f2c5040a0dfa0
 - Date: 2012/2/10 13:58:58

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

## ��������

###module_cn

  - ����`module.require`������(line 313)��

>Note that in order to do this, you must get a reference to the `module`
>object.  Since `require()` returns the `exports`, and the `module` is
>typically *only* available within a specific module's code, it must be
>explicitly exported in order to be used.

>ע�⣬Ϊ��ʹ��require�����������Ȼ�ö�`module`��������á���Ϊ`require()`�᷵��`exports`��
>����`module`ͨ��ֻ�������ģ���������Ч������ֻ����Ҫ�õ�ʱ�ŵ�����

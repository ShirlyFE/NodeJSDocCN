## console

������stdout��stderr��ӡ��Ϣ����������web������ṩ�Ŀ���̨������������
������������Ϣ�ᱻ���͵�stdout��stderr�С�


### console.log()

��stdout������һ�д�ӡ��Ϣ�����������������`printf()`�����������ܶ�����������磺

    console.log('count: %d', count);

����ڵ�һ���ַ����в�û���ҵ���ʽ����ǩ����ô���֮���ÿ������ʹ��`util.inspect`������
�μ�[util.format()](util.html#util.format)��ȡ������Ϣ��

### console.info()

��`console.log`��ͬ��

### console.warn()
### console.error()

��`console.log`���ƣ�ֻ����stderr�д�ӡ��Ϣ.

### console.dir(obj)

��`obj`ִ��`util.inspect`���������ѷ��صĽ���ַ�����ӡ��stderr��

### console.time(label)

������ʱ����

### console.timeEnd(label)

��ֹ��ʱ�����������������磺

    console.time('100-elements');
    for (var i = 0; i < 100; i++) {
      ;
    }
    console.timeEnd('100-elements');

������ע����󽫴�ӡ�������ѭ����ʹ�õ�ʱ�䣩

### console.trace()

��stderr�д�ӡ��ǰ�ű�ִ��λ�õĵ��ö�ջ��

### console.assert()

��`assert.ok()`��ͬ��


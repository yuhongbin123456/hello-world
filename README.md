String a = new String("123");
		String b = new String("123");
		String c = "123";
		String d = "123";

		System.out.println("a值对应的hashcode是："+a.hashCode());
		System.out.println("b值对应的hashcode是："+b.hashCode());
		System.out.println("c值对应的hashcode是："+c.hashCode());
		System.out.println("d值对应的hashcode是："+d.hashCode());

		System.out.println("a对应内存地址中的hashcode是："+System.identityHashCode(a));
		System.out.println("b对应内存地址中的hashcode是："+System.identityHashCode(b));
		System.out.println("c对应内存地址中的hashcode是："+System.identityHashCode(c));
		System.out.println("d对应内存地址中的hashcode是："+System.identityHashCode(d));

		System.out.println("a==b:" + (a == b));
		System.out.println("c==d:" + (c == d));
		System.out.println("a==c:" + (a == c));

		System.out.println("a.equals(b):" + (a.equals(b)));
		System.out.println("c.equals(d):" + (c.equals(d)));
		System.out.println("a.equals(c):" + (a.equals(c)));
    
    
    
    输出结果为：
    a值对应的hashcode是：48690
    b值对应的hashcode是：48690
    c值对应的hashcode是：48690
    d值对应的hashcode是：48690
    a对应内存地址中的hashcode是：722080798
    b对应内存地址中的hashcode是：581882789
    c对应内存地址中的hashcode是：63506285
    d对应内存地址中的hashcode是：63506285
    a==b:false
    c==d:true
    a==c:false
    a.equals(b):true
    c.equals(d):true
    a.equals(c):true


* 有参考价值的文件
    * 3_nilchan, 展示了 nil chan 的机制, 即 select 会block， send will sliently fail.
    * tomb, 用于展示怎么通过tomb库，来通知channel的死亡, 没看懂有什么用途
    * timeout 这个机制很common了
    * 8_panicked, sending to closed channel would cause panic
    * 10_indeterminate: type 的判断的方式之前没怎么见过 switch typ := variable.(type) {}
    * 11_load: 这个文件的http的反向代理，还有go语言中类似js的ctx语法的指定，在 handler & startListening 方法的灵活运用上
    

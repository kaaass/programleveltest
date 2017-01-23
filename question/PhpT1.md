# Php试题T1
运行以下php代码将会输出什么？
```php
$a = "b";
$b = "c";
$c = "a";
function a($b){
global $a;
global $$b;
$$a = $b;
$$b = $a;
return $$a;
}
$$a = a($a);
$$a = a($$a);
echo(a($$$a));
```

# springboot04

1 @RestController相当于同时使用@Controller和@ResponseBody注解

2 返回视图使用@Controller，不能使用@ResponseBody

3 SpringBoot的静态资源默认目录为/static、/public、/resources、和/META-INF/resources，默认映射路径都是/。

4 SpringBoot默认会按照META-/resources > resources > static > public 的优先级寻找对应的资源文件并返回第一个找到的文件。


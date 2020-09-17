
cookie和session？⭐⭐
① cookie 只能存储 ASCII 码，而 session 可以存储任何类型的数据。

② session 存储在服务器，而 cookie 存储在客户浏览器中，容易被恶意查看。。

③ session 的运行依赖 session id，而 session id 存在 cookie 中，叫做 JSESSIONID。如果浏览器禁用了 cookie ，同时 session 也会失效（可以通过其它方式实现，比如在 url 中传递 session_id）

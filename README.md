//获取所有用户信息
http://localhost:3000/users

//获取id为1的用户的信息
http://localhost:3000/users/1

//获取公司的所有的信息
http://localhost:3000/companies

//获取单个公司的信息id为1的公司
http://localhost:3000/companies/1

//获取所有公司id为3的所有用户
http://localhost:3000/companies/3/users

//根据公司名字获取信息
http://localhost:3000/companies?name=Apple

//根据多个名字获取信息
http://localhost:3000/companies?name=Apple&name=Microsoft

//获取一页中只有两个数据的
http://localhost:3000/companies?_page=1&_limit=2

//根据名字升序排序  升序asc   desc是降序
http://localhost:3000/companies?_sort=name&_order=asc

//获取年龄在30到30以上的
http://localhost:3000/users?age_gte=33

//获取年龄在32到40之间
http://localhost:3000/users?age_gte=32&age_lte=40


//搜索用户信息
http://localhost:3000/users?q=e





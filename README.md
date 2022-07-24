## Community Board By Spring Boot

> 原先的專案後端使用的是Java Servlet+JSP
>
> 此repository將之改寫為Spring Boot架構
>
> 附上OpenAPI文件(ymal檔)，可複製至 [https://editor.swagger.io/](https://editor.swagger.io/ "Swagger Editor 線上版")  觀看

### 使用Spring boot建構專案後端API

### API ###

- 管理者(社區保全或警衛) CRUD

	1. 新增管理員資料
	2. 查詢管理員資料
	3. 修改管理員資料
	4. 刪除管理員資料

----------
- 社區公告欄(例如里長公告或停電停水等公告) CRUD

	1. 新增公告欄訊息
	2. 查詢公告欄訊息(可分類查詢)
	3. 修改公告欄訊息
	4. 刪除公告欄訊息

----------
- 住戶 CRUD
	1. 新增住戶資料
	2. 查詢住戶資料(模糊查詢姓名、分頁配置、排序)
	3. 修改住戶資料
	4. 刪除住戶資料

----------
- 社區設施租借 CRUD
	1. 新增租借
	2. 查詢租借狀況(模糊查詢姓名、場地、日期、預定時間(ex: 10:00-12:00)、可排除過期預定)
	3. 修改租借
	4. 刪除租借

### 持續新增中

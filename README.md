# TODOS RAILS API

---
---
* Get Started
1. Clone this repository
 	```
 	git clone https://github.com/gdhuper/Todos-Rails-Api.git
	```
2. Run 

	```
	rails db:migrate
	```
3. Start the server 
	```
	rails server
	```

Download [httpie](https://httpie.org/) (HTTP CLI for terminal)
---
---

* To get tasks list:
```
http :{Port}/todos
```
* To add a new Task:
```
http POST :{Port}/todos title=Mozart created_by=1
```
* To Update a task

```
 http PUT :{Port}/todos/1 title=Beethoven
```
* To delete a task
```
http DELETE :{Port}/todos/1
```

# 📝 TaskManager

A clean, modern task manager built with **Spring Boot** (Java) for the backend and **vanilla HTML/CSS/JavaScript** for the frontend.
---

## 🚀 Features

- ✅ Create, Read, Update, Delete (CRUD) Tasks
- ✅ Filter by Pending / Completed
- ✅ Mark tasks as completed
- ✅ Edit or delete tasks
- ✅ Responsive UI with clean animations
- ✅ REST API built with Spring Boot
- ✅ Stylish UI with Tailwind CSS + Feather icons

---

## 📦 Backend: Spring Boot

### 📁 Technologies

- Java 17 or 21
- Spring Boot 3.1+
- Spring Data JPA
- PostgreSQL
- Maven

### 📄 Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/taskmanager.git
   cd taskmanager

2. **Configure PostgreSQL**

    * Create a database named `taskdb`
    * Update credentials in `src/main/resources/application.yml`:

      ```yaml
      spring:
        datasource:
          url: jdbc:postgresql://localhost:5432/taskdb
          username: postgres
          password: yourpassword
      ```

3. **Run the backend**

   ```bash
   ./mvnw spring-boot:run
   ```

   > Your backend will be live at: `http://localhost:8080`

---

## 🌐 Frontend: HTML + CSS + JavaScript

### 📁 Location

Place your HTML file in:

```
src/main/resources/static/index.html
```

### ✅ Features

* No frameworks required
* Uses `fetch()` to call Spring Boot REST APIs
* Feather icons
* Vanta background animation
* Tailwind CSS (via CDN)

### 🧪 Sample Screenshot

> *(Add screenshot here)*
> `![Screenshot](screenshot.png)`

---

## 🔗 API Endpoints

| Method | Endpoint          | Description     |
| ------ | ----------------- | --------------- |
| GET    | `/api/tasks`      | Get all tasks   |
| GET    | `/api/tasks/{id}` | Get task by ID  |
| POST   | `/api/tasks`      | Create new task |
| PUT    | `/api/tasks/{id}` | Update task     |
| DELETE | `/api/tasks/{id}` | Delete task     |

---

## 🛠️ Future Improvements

* Tag filtering
* Due dates & reminders
* Drag-and-drop tasks
* Dark mode
* Mobile-first enhancements

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.

---

## 📜 License

MIT

---

## 👨‍💻 Author

* **Your Name** – [Rajeev Nayan](https://linkedin.com/in/imrajeevnayan)



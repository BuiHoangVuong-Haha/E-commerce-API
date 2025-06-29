# 📘 Category API Specification

| API Name        | Endpoint                                 | Method | Purpose                      | Request Body | Request Parameters                         | Response         |
|------------------|-------------------------------------------|--------|-------------------------------|---------------|---------------------------------------------|------------------|
| Create Category  | `/api/admin/category`                     | POST   | Create a new category         | Category      | None                                        | CategoryDTO      |
| Get Categories   | `/api/public/categories`                 | GET    | Retrieve a list of categories | None          | pageNumber, pageSize, sortBy, sortOrder     | CategoryResponse |
| Update Category  | `/api/admin/categories/{categoryId}`      | PUT    | Update an existing category   | Category      | categoryId                                  | CategoryDTO      |
| Delete Category  | `/api/admin/categories/{categoryId}`      | DELETE | Delete an existing category   | None          | categoryId                                  | CategoryDTO      |

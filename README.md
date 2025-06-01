# Crud_Notas_Law_Code - Veredictum  

# 📦 API de Notas Fiscais


---

## 🚀 Endpoints


### 📄 Listar todas as notas fiscais
`GET`  
http://localhost:8080/notas


---

### 🔍 Buscar nota fiscal por ID  
`GET`  
http://localhost:8080/notas/1

---
### 🧾 Buscar notas fiscais por nome do cliente
`GET`
http://localhost:8080/notas/buscar-por-cliente?nome=João

---
### 📅 Buscar notas fiscais por data de criação
`GET`
http://localhost:8080/notas/buscar-por-data?data=2024-08-10

---

### ➕ Criar nova nota fiscal
`POST`  
http://localhost:8080/notas

#### 🔧 Body (JSON)

{
 "clienteId": 1,
  "valorTotal": 199.99,
  "dataCriacao": "2024-08-10"
}

---
### ❌ Excluir nota fiscal
`DELETE`
http://localhost:8080/notas/1



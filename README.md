1. Se utilizó React con Typescript, se creó una tabla en supabase llamada tasks con los campos

●	id
●	title
●	completed
●	created_at

2. Para que estos puedan ser leídos por en archivo types.ts, este archivo
contiene los tipos de cada dato, id es un string al igual que title, completed, createdAt

export  interface  Task { 
  id : string ; 
  title : string ; 
  completed : string ; 
  createdAt : string ; 
}

3. Se creó un archivo .env para enlazar el supabase con el Proyecto
mediante su url y su llave

VITE_SUPABASE_URL=https://xrhbnaonbwhyuzaiwcyx.supabase.co
VITE_SUPABASE_PUBLISHABLE_KEY=sb_publishable_WZeHsP-XaTU2ntOhi1CMiQ_x4uHwbsN


4. Se Creó el directorio de Componentes con los archivos List.tsx, Item.tsx, Form.tsx


5. Se Creó un archivo .gitignore para ignorar el directorio de node_modules


Fuentes Utilizadas:

- https://codeinprogress.dev/article/crear-lista-tareas-react-typescript
- https://www.freecodecamp.org/news/how-to-build-a-todo-app-with-react-typescript-nodejs-and-mongodb/
- https://medium.com/@zhr77fth/building-a-comprehensive-todo-list-using-react-js-and-typescript-7e0aea2de6f9

``mermaid
graph TD;
    A[Usuario ingresa texto en el campo de nota] --> B[Usuario hace clic en 'Save'];
    B --> C[El navegador envía solicitud POST al servidor];
    C --> D[El servidor procesa la solicitud y guarda la nota];
    D --> E[El servidor responde con éxito];
    E --> F[El navegador actualiza la lista de notas];
    F --> A[La nueva nota se muestra en la página];
    
``


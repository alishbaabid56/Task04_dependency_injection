## Dependency Injection

FastAPI’s Dependency Injection system lets you extract reusable logic (e.g. authentication, database connections, common parameters) into standalone functions or classes, then “inject” them into your endpoints with `Depends()`.  

**Key Benefits:**  
- **Reusability:** Write shared code once and reuse across multiple routes  
- **Separation of Concerns:** Keep endpoint handlers focused on business logic  
- **Testability:** Easily swap real dependencies for mocks in tests  
- **Organization:** Structure complex setups (e.g. nested dependencies) cleanly  

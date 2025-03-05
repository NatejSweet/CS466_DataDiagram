# CS466_DataDiagram
```mermaid
flowchart TD
    A["App"] -- GET request --> B["Api"]
    B -- Query Database --> C["Database"]
    C -. Data .-> B
    B -. GET response .->A
```

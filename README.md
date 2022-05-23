"# Content-Management-System" 
```mermaid
graph TD;
    PublicArea-->Navigation;
    PublicArea-->PageContent;
    Navigation-->ReadOnly;
    PageContent-->ReadOnly;
```
```mermaid
graph TD;
    AdminArea-->LoginPage;
    LoginPage-->Form;
    LoginPage-->Password;
    Form-->Username;
    Password-->Username;
    Username-->AdminMenu;
    AdminMenu-->ManageContent;
    AdminMenu-->Logout;
    ManageContent-->Logout;
    ManageAdmins-->Logout;
```
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
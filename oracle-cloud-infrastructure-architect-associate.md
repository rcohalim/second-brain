# OCI Architect Associate

## 1. Identity and Access Management
### Identity
- Authentication (AuthN), username and password
- Integration with existing identities and applications
  
### Access Management
- Authorization (AuthZ), who can access what
- RBAC
- Granular permission
  
### Components
- Identity Domains (Container for users, groups, and applications)
- Users
- Principals
- Groups (Collection of users)
- Dynamic Groups
- Policies
- Compartments (Container to isolate and secure resources in OCI tenancy)
- Resources
- Federation
- Network Sources
- Active Directory Bridge: to connect managed users list from an external identity source, i.e. Microsoft AD.
- Default Domain: automatically created with 2 groups, `All Domain Users` and `Adminiistrators`. Can't be deleted.
<img width="1244" height="468" alt="image" src="https://github.com/user-attachments/assets/3aaa9542-4130-4264-b823-e7363baee228" />

### ID Types
- Free
- Oracle Apps Premium (For oracle apps)
- Premium (Enterprise)
- External User (Non-employee and consumer)

### Managing User
<img width="1305" height="729" alt="image" src="https://github.com/user-attachments/assets/42c1de9a-ead9-47a4-b6b5-e0a064c14471" />

### Understanding Admin Role
- Identity Domain Admin
- Security Admin
- Application Admin: Manage application lifecycle, including creation, updates, activations, deactivation, deletion and access management for groups and users
- User Admin: Manage users, groups, and group memberships for an ID
- User Manager: Handle account updates, activation, deactivation, removal and password-related
- Help Desk Admin: Oversee user details, unlock accounts, and manage password-related tasks, including resets and bypass code generation
- Audit Admin: Run reports for ID.

### Policies
<img width="1302" height="588" alt="image" src="https://github.com/user-attachments/assets/8349a5c0-209e-45e6-8b87-894a7b77b1ae" />
<img width="1291" height="726" alt="image" src="https://github.com/user-attachments/assets/7fbd2669-14d0-43ae-b71c-9438551b4ddf" />
<img width="1295" height="716" alt="image" src="https://github.com/user-attachments/assets/078a6655-3677-4394-b974-75e6c6637687" />
<img width="1297" height="708" alt="image" src="https://github.com/user-attachments/assets/caeee57c-17f5-4f6d-8af8-8c663ca28def" />

### Compartments
- Global concept: can span across multiple region
- Compartments can be nested up to 6 levels
- Quota
<img width="1286" height="722" alt="image" src="https://github.com/user-attachments/assets/92c4c8b6-d29b-49f1-8c71-40f027914402" />
Types of Quota Policy Statement:
- Set: set the max number of resource can be used for a compartment
- Unset: reset quotas back to the default limits
- Zero: remove access to a cloud resource for a compartment





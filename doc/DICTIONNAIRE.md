## Dictionnaire de données

| Name               | Signification                         | Type                |
| :----------------- | :------------------------------------ | :------------------ |
| Id_person          | Id of person                          | Int(auto_increment) |
| Name_person        | Name of person                        | Varchar             |
| FirstName_person   | First name of person                  | Varchar             |
| Email_person       | Email of person                       | Varchar             |
|                    |                                       |                     |
| Id_role            | Id of role                            | Int(auto_increment) |
| Type_role          | Type of role                          | Varchar             |
|                    |                                       |                     |
| Id_resource        | Unique id for role                    | Int(auto_increment) |
| Name_resource      | Name of resource                      | Varchar             |
| Type_resource      | Type of resource                      | Varchar             |
| Avaibility_date    | Resource availability date            | Date                |
| Growth_date        | Date of resource growth               | Date                |
|                    |                                       |                     |
| Id_profile         | Unique id for profile                 | Int(auto_increment) |
| Profile_avatar     | Avatar for profile user               | Varchar             |
| Pseudo             | Pseudo for user                       | Varchar             |
| Password           | Login password                        | Varchar             |
| Score              | User score                            | Integer             |
| Registration_date  | Date of registration                  | Date                |
|                    |                                       |                     |
| Id_stack           | Unique id for the stack               | Int(auto_increment) |
| Stack_name         | Name of stack                         | Varchar             |
| Logo_stack         | Logo of the stack                     | Varchar             |
| Stack_theme        | Theme of the stack                    | Varchar             |
| Level              | User level                            | Varchar             |
|                    |                                       |                     |
| Id_book            | Unique id for a book                  | Int(auto_increment) |
| Title_book         | Title of the book                     | Varchar             |
| Language           | Language of the book                  | Varchar             |
| Page_number        | Number of pages in the book           | Integer             |
| Category           | Category of the book                  | Varchar             |
| Start_reading_date | Starting date of the reading          | Date                |
| End_reading_date   | End date of reading                   | Date                |
| ISBN               | Book identification number            | Integer             |
| Year               | Year of publication of the book       | Integer             |
| Cover_image        | Cover of the book                     | Varchar             |
| Author_book        | Author of the book                    | Varchar             |
|                    |                                       |                     |
| Id_video           | Unique id for a video                 | Int(auto_increment) |
| Title_video        | Title of the video                    | Varchar             |
| Plateform          | Platform where you can find the video | Varchar             |
| Duration_video     | Duration of the video                 | Integer             |
| Author_video       | Author of the video                   | Varchar             |
|                    |                                       |                     |
| Id_tra             | Unique id for a training              | Int(auto_increment) |
| Name_tra           | Name of the training                  | Varchar             |
| Duration_tra       | Duration of training                  | Integer             |
| Type_tra           | Type of training                      | Varchar             |
| Start_date         | Start date of the training            | Date                |
| Closing_date       | End date of the training              | Date                |
| Organization_name  | Name of the organization              | Varchar             |
| Organization_logo  | Logo of the organization              | Varchar             |

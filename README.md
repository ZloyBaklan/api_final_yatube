# api_final
The frontend and view functions of the posts application are excluded from the project.

When the project is launched, 
documentation for the Yatube API will be available at http://127.0.0.1:8000/redoc/. 
The documentation is presented in Redoc format.

Viewsets are used.
JWT tokens are used for authentication.
Unauthenticated users have read-only access to the API. 
The exception is the / follow / endpoint: only authenticated users are allowed access to it.
Authenticated users are allowed to modify and delete their content; otherwise, read-only access.
Adding new users via the API is not required. 

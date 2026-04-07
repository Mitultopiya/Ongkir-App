#### Front-End Endpoit Routes:

| Nama | Route Name |
| -----| -----------|
|  Home | http://localhost:3000
|  Login  | http://localhost:3000/signin
|  Register  | http://localhost:3000/signup
|  Profile | http://localhost:3000/profile
|  Activation Account  | http://localhost:3000/activation/:id
|  Forgot Password | http://localhost:3000/forgot-password
|  Reset Password | http://localhost:3000/reset-password/:id'
|  Resend Token | http://localhost:3000/resend-token'
|  Verification Token Activation Account | http://localhost:3000/verify-activation/:id'
|  Verification Token Reset | http://localhost:3000/verify-reset/:id'
|  Logout | http://localhost:3000//logout'

#### Back-End Endpoit Routes:

| Nama | Route Name | Request Method |
| -----| -----------| ---------------|
|  **User Endpoint** | | |
|  Login | http://localhost:3001/api/user/login | POST
| Register  | http://localhost:3001/api/user/register | POST
|  Resend Token  | http://localhost:3001/api//user/resend-token | POST
|  Forgot Password | http://localhost:3001/api/user/forgot-password | POST
|  Reset Verification  | http://localhost:3001/api/user/reset-password/verify/:id | GET
|  Reset Password | http://localhost:3001/api/user/reset-password/:id| POST
|  Activation Account | http://localhost:3001/api/user/activation/:id' | GET
|  Social Login | http://localhost:3001/api/user/social-login' | GET
|  Social Register | http://localhost:3001/api/user/social-register' | GET
|  **Profile Endpoint** | | |
|  Edit Profile  | http://localhost:3001/api/user/profile/:id' | GET
|  Update Profile | http://localhost:3001/api/user/profile/:id | POST
|  **Ongkir Endpoint** | | |
|  City  | http://localhost:3001/api/cekongkir/city' | GET
|  Province  | http://localhost:3001/api/cekongkir/prov | POST
|  Kabupaten  | http://localhost:3001/cekongkir/kab' | GET
|  Cost | http://localhost:3001/api/cekongkir/cost | GET
|  **Social  Endpoint** | | |
|  Google  | http://localhost:3001/auth/google' | GET
|  Facebook  | http://localhost:3001/auth/facebook | POST
|  Github  | http://localhost:3001/auth/github' | GET

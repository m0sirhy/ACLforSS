In this app I build ACL  “roles and permissions” on laravel 5.8 application. using spatie composer package. 
<br>
They provide how to assign role to user, how to assign permission to user and how to assign Permission assign to roles.
<br>
Roles and Permissions through you can create several types of users with different role and Permission
 I mean some user have only see listing of items module, some user can also edit items Modules, for delete and etc.
<br>
In this App I create three modules as  :User ManagementRole ,ManagementProduct, ManagementAfter register user, you don't have any roles, so you can edit your details and Assign admin role to you from User Management. After that you can create your own role with Permission like role-list, role-create, role-edit, role-delete, product-list, product-create, Product-edit, product-delete. 
You can check with assign new user and check that.
<br>
tO run this Project //

1st->composer update
<br>
Seeders
<br>

-> php artisan db:seed --class=PermissionTableSeeder
<br>
-> php artisan db:seed --class=CreateAdminUserSeeder
 <br>
Defualt User:
Email: admin@gmail.com

Password: 123456

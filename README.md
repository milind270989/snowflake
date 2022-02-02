# snowflake
This repo would contain all snowflake POC stuff

**a) Procedure sp_find_users_and_roles:** <br/>
<br/>
  -- Use this procedure to populate a table i.e user_roles to fetch all users and their associated roles on snowflake <br/>
  -- This procedure will be helpful when someone doesn't has ACCOUNTADMIN privileges but has SECURITYADMIN privileges <br/>
  -- More details regarding step-by-step implementation can be found on the below medium article: <br/>
     https://medium.com/@milind270989/snowflake-to-fetch-all-users-and-their-roles-allocated-to-them-ad7ea34fb8d9 <br/>
 
 [Note: There may be multiple ways to do this but I found this method effective and useful since we don't need to run behind ACCOUNTADMIN to get access to snowflake db and whenever someone needs a full report of users and their roles; just execute this procedure] <br/>

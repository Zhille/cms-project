# Procedural PHP - CMS project 

# Home page
So, let's start from main page which is index.php, in index.php have all the post's that are made by Admin or Subscriber ( Subscriber have limited access and only they can see is 'published' post's, Admin can see all of them ).
All post's have their category and that is one thing that make them different and possible to sort. If u want to sort them, the one way of doing that is by clicking at one them at navigation or side bar. The second way of sorting post's is by post creator, if you click on any post creator name browser will bring you to page where will be displayed all the post's for that specific user. If you want to search some post's or one specific post you can do that by using 'blog search', for example, if you want to see only post's about PHP just type 'PHP' in search box and all post's wich have some relation about PHP will be displayed. In this case, web site have a lot of post's so all the post's are separated by using pagination which is dymanic pagination and number of pages deppended's of number of post's. For contacting support ( in this case Admin ) go to > Contact < bar, and easily send the e-mail. You can make your own profile at > Register < bar, your permission will be limited becaouse your role is 'Subscriber' by deafult. Login box is on the right side bar and at navigation bar too, if your username and password are correct you will be moved to Admin section if not, YOURE ALLOWED TO RESET YOUR ADASDSADSADSADASDDASD
# Admin section
· On the main page of Admin section will be displayed web site stastistic supported with google chart. Navigation bar is on the left side, the first bar is drop-down type, first option is:
View all posts: At this page you can clearly see all specifications for specific posts, in this table you can magane post data like,view, edit, delete, see all the comments for that specific post, views count, and there is an checkbox which can select multiple posts and edit,clone,delete or make them 'publish/draft' at once. Second options is:
Add post: this page is for adding post's, first input is type text and it's for post Title, after that is select with dynamic otpions ( pulling from db ), again text input for post author name, next select is for post status which is have draft and published option's. At the end is post content whiich have CKEditor implemented.
Categories page is simple one, all is doing is adding new categories and deleting or editing existing ones.
Comment page is standing for all comments from web site, each comment have 'In Response to' field, by clicking on it you will me moved directly to that specific post -> comment. Comment can be deleted, approved or unapproved, if is unapproved ofcourse comment will not be displayed. User drop-down bar is absolutly similar to Post's one, ofcourse with the content is for User in this case. User bar is not available for users with subscriber role. The passwords are not allowed not even for Admin. The last bar is Profile, here user can edit his own profile as chacging email, username, password ( which is all the time hashed ).

# Hope you like my PHP-CMS project. If you interested check out rest of my projects. 
Have a great one! :) 
-



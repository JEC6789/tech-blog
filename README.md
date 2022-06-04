# Tech Blog
* server actually runs: ✔
* comment get: ✔
* comment post: ✔
* comment delete id: ❌*
* post get: ✔
* post get id: ✔
* post post: ✔†
* post put: ✔
* post delete id: ✔
* user get: ✔
* user get id: ✔
* user post: ✔
* user post login: ✔
* user post logout: ✔
* user put: ✔
* user delete: ✔
* dashboard get: ✔
* dashboard get new: ✔
* dashboard get edit: ✔
* home get: ✔
* home get login: ✔
* home get signup: ✔
* home get post id: ✔

*`/api/comments/:id` always returns 404 w/o body; it's like the route doesn't even exist

†entering something too long for the post content throws an error; appears to be a limitation of SQL
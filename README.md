# Wetube Reloaded

#### Think domain in URL perspective
/ -> Home
/join -> Join
/login -> Login
/search -> Search

## With Router

### users Router
/users/:id -> See User
/users/logout -> Log Out
/users/edit -> Edit My Profile
/users/remove -> Remove My Profile

### videos Router
/videos/:id -> See Video(via id of video)
/videos/:id/edit -> Edit Video
/videos/:id/delete -> Delete Video
/videos/upload -> Upload Video

> Router groups URL based on their subject



### Best way to organize this is to by Router
# Thoughts
My good ideas which may come anytime are recorded here so that they shall not be forgotten.

## The View layer should only process the request
Right now, the view layer is handling business logic and shits. It should make sure the request is appropriate or of right format. Updating, deleting and other stuffs like that should be handled by the Serialization layer, and better yet, a Service layer.

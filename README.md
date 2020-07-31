# Go Koans

My run through the Go Koans. Welcome!

I stumbled across the Go Koans on another repo, and thought the objective was to replace the __vars__ in the setup file to somehow make it through all the tests.
I made it pretty far before I realized this was not the right way.

Now, I have three terminal windows open side by side.

On the left, I nano the .go file I am currently working on

In the middle, I ran `fswatch -0 . | xargs -0 -n 1 -I {} go test`

On the right, I have the README open to take notes and git

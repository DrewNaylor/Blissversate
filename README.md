# Blissversate
ActivityPub-federated commenting system that'll possibly be based on Commento (or maybe Isso? not sure what I'll fork yet) so I don't have to start from scratch. Repo exists just so I don't forget the idea for now.

My goal is to have it be a usable alternative to Disqus (including real-time discussion stuff like "x new comments below/above" and "x replies" when a comment with replies is in view) without all the weird ads and bugs, and with improved privacy.

Other planned features include the option to hide or show downvote counts (like my no-downvote-display extension), hide or show upvote counts, theme choices, some fun commands that do things based on the users in a discussion and other stuff like that (idea from a certain Disqus enhancer extension). Commands can be turned off by the instance, and themes and upvote/downvote counts can by set with defaults by the instance and changed by the user. Of course, blocking and muting profiles like Twitter will be available, where both shows a button to show the comment (if possible in ActivityPub), blocking prevents the profile from seeing your profile, and muting just hides their stuff. Word or phrase filters for muting to hide comments will be available too. Obviously instance blocking will be available for both profiles and instances. There should also be an option for users to hide the "x user(s) are/is typing" and "x comments above/below" to make it less addicting.

Something I don't know how I'll implement it is to allow users to sign in with their instance on other websites that aren't associated with their instance, like alternate Mastodon web UIs. Guess I could look at how they do it. The reason for this is it'll mainly be an embedded thing to show comments on blog posts and stuff.

Also for instances that don't allow commands, should it just not let command comments federate instances that don't allow them? No idea.

Like Disqus, there will be a "Recommend" button for discussions that will work like boosting on Mastodon. It'll federate to other instances that way. Should upvotes on comments work as a boost too? Maybe I should check Kbin for that, as I need to know how to also handle downvotes.

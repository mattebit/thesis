# Wendy plugin

-   It was thought focusing on testing just OAuth and OIDC deployments
-   the biggest problem is that the language was limited in testing SSO (p.2 "Operation's main function is the search of a regex pattern inside HTTP messages exchanged during the SSO process"
-   Wendy's objective was to design a language that allows the user to define tests in a more natural way, being able to specify tests without having to modify the code of the plugin (as it was before)
-   p.17, Message Type in passive test can be only of 4 types
-   p.17 In active tests the edit or deletion is only possible to parameters of the message, limiting the fact that an user could want to select various type of parameters, or just can't select encoded parameters
-   p.17 Previous oracle was just checking the correct edit of the messages and searching that a page has "error" in it
-   p.20 Current limitations: cannot save strings or values, cannot execute multiple operations in the same test
-   p.29 The future works and features are all implemented by me

# to talk

talk about this thing
Note for the definition of the track: to have a successfull oracle i suggest to define a track that not only does the login of the user, but also performs some actions on the final page, this way the result of the track is more complete. (i.e. if we just tell to login, the track will not try to act on the logged page, this way the plugin has no clue on if the final page contains an error or not)


Immagine PKCE downgrade test
https://danielfett.de/2020/05/16/pkce-vs-nonce-equivalent-or-not/

https://danielfett.de/img/plantuml/b936c9ccd8c1ca76156cef40d4262ba1fa929fc43214cf2549d44176ba5b458b.svg
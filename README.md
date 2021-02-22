# Synchro Music Player

The objective of this application is to prompt the user, upon opening the app, to describe their mood at the present moment. In the blueprint diagrams I have constructed in my notepad, the user will have the ability to bypass this question. The reasoning for this is that I intend for the application to dual-serve as a regular music player which is not concerned about the user mood but simply allows for the typical search and playing of music. 

Some problems I have found with other players like Spotify are the amount of crashes and drops of connection during ads. When such events occur, the entire app must be restarted as it demands the completion of the ad for music to resume playing, and obviously it cannot do that during a freeze of the ad. Furthermore, the desktop application of Spotify used to have a feature where an Album could be "liked", and subsequently all the songs within the album would be "liked" as well. However, the behavior where "unliking" a specific song within that album which would lead to that song's removal from the liked album is no longer in place. This is a useful feature to have in the likely event that the user doesn't like all the songs of the album and wishes to only hear the ones they like.

Other mobile apps like SoundCloud are too inflexible in their removal and addition of songs to user-defined playlists. This is just a poor design decision and be fixed if I reason well how I, or anyone, as a user, will find it most convenient to add or drop songs from their playlists. The navigation from song to song, while music is playing in the background, leaves much to be desired from a design perspective, specially the control elements at the bottom of the screen. This is something I want to explore more about. 

## Inquisitor View

Asking user for mood preferences / regular playlist usage

## Playlist List View

"Hub" for user playlist selection

Contains two types of playlists:

* Liked
* User-Defined

## Album View

Displays information about the album. Also lets user browse and play its items.


## Technologies

Some of the technologies which I intend to incorporate into this project are as follows:

* **SwiftUI**
  * I want to test out the possibilities of UI Design from a non-UIKit perspective. Many elements from UIKit are transferable into SwiftUI, should the need arise to use them.
* **MongoDB / Realm**
  * I'm more familiar with the Realm architecture rather than Firebase, so this was an arbitrary decision. That said, I wanted to learn MongoDB anyway since I don't know any database querying besides SQLAlchemy. Mongo is document-data based, or noSQL, which makes it easier to learn from its JSON-like format but might hinder my understanding of databases later on.
* **GraphQL / Apollo**
  * Apollo is just the mechanism to interact with GraphQL data through the iOS ecosystem, or more specifically the Swift language. Rather than trying the typical API endpoint fetching game, it'd be interesting to see how I can incorporate it since Mongo Realm offers their own GraphQL services and endpoints.
* **Docker**
  * Is it possible to implement some containerization for this project? I don't understand enough about this technology to see if it would make sense. Certainly it won't be packaged into the product app but perhaps I could use it to do some sort of testing at some level. Not sure, will come back later.


## Diagram of the Application Flow

Link to the [Wireframe](https://whimsical.com/synchro-H4L45LKzkcG6CFVjWG87eA).

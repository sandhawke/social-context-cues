
This is a rough proposal for an approach to solving [https://github.com/swicg/general/issues/3 Socially Acceptable Search #3].  It's based the idea of content warnings, as soon in Mastodon and much earlier in [http://www.livejournal.com/support/faq/75.html LiveJournal's lj-cut].

I'm framing the problem like this:

1. Some content is fully, happily public. The author is happy to have it seen accidentally, in random search results, etc.
2. Some content is sensitive enough that one needs access control.  No one should be allowed to see it unless the author has granted them permission.  Sometimes that permission is to a large group, but it's still access controlled.
3. Finally, some content is kind of in between.  It's not exactly private, and the author is sometimes happy to have strangers come across it, but it's also somewhat sensitive, and if it were to show up in search results unpleasant, unpleasant things would happen a little too often.

This proposal is about handling that third class.

The idea is that we make these sensitive items (group 3 above) be opt-in, in the search facility.  They would not show up by default, but the search engine would mention there are other results currently being hidden, and give you a way to open an opt-in panel.  The opt-in categories would be fairly specific.  And the opt-in might in some cases involve agreement.  Not just "I want to see this", but "I accept all responsibility for what happens when I see this, and agree to act in a respectful manner".  Or something like that.

No, this wont stop bad actors, but they can just make a bad-actor search engine anyway.   This might, however, significantly reduce the number of people who behave badly in response to posts they see because they're coming from an emotionally unbalanced place, or because they think what they're doing is fine.   My own belief is that's most of the people behaving badly online.  I know I'm a bit naive.

I think the content-warning mechanism for this would have to be somewhat more flexible than in Mastodon.  In particular, one needs to be able to add it after-the-fact.  I think also it'd be good if 3rd parties could apply these warning-labels, although I'd want the author to be able to apply non-warning-labels, too, and then if they contract the system can figure out which to believe more, somehow.   (If there's no trust data on either party, I'd trust the author more.  I might give mentioned parties some priority, too.)

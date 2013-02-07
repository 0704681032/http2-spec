
HTTP/2.0 Specification
======================

This is the working area for the [IETF HTTPbis Working
Group](http://trac.tools.ietf.org/wg/httpbis/trac/wiki) draft of HTTP/2.0.

Published drafts can be found on the [IETF tools
site](http://tools.ietf.org/html/draft-ietf-httpbis-http2), and are marked
with tags here.

The source for our current draft is
[draft-ietf-httpbis-http2.xml](draft-ietf-httpbis-http2.xml), using the
[RFC2629 format](http://xml.resource.org/public/rfc/html/rfc2629.html).

An HTML copy of the current (unsubmitted) draft can be found
[here](http://http2.github.com/http2-spec/draft-ietf-httpbis-http2.html).


Providing Feedback
------------------

Before submitting feedback, please familiarise yourself with our current
issues list, and see [our home
page](http://trac.tools.ietf.org/wg/httpbis/trac/wiki) for more information
about participating.

1. The best way to provide feedback and ask questions is sending an e-mail to
[our mailing list](http://lists.w3.org/Archives/Public/ietf-http-wg/). This
will assure that the entire Working Group sees your input in a timely fashion.

2. If you have editorial suggestions, you can fork this repository and submit
a pull request; this is the lowest friction way to get such changes in. While
this method can also be used to suggest more substantial changes, they'll need
to be discussed on the list first.

3. You can also create an issue on github. Note that such issues may be
changed or pre-emptively closed, based upon their relevance to our work. If
you disagree with how your issue is handled, please bring it up on the mailing
list. 

4. Finally, you can make comments on individual commits in Github. Note that
this feedback is processed only with best effort by the editors, so it should
only be used for quick editorial suggestions or questions, not substantial
feedback.


Working With the Draft
----------------------

If you're an editor, or forking a copy of the draft, a few things to know:

* We push to both the master and gh-pages branches, to keep the HTML view in
  sync. See [this
  tip](http://brettterpstra.com/2012/09/26/github-tip-easily-sync-your-master-to-github-pages/)
  to make that easy; after doing that, you'll only need to "git push" (NOT
  "git push origin master").
* You'll need xml2rfc, java and saxon available. You can override the default
  locations in the environment, if you use "make -e".
* Making the txt and html for the latest draft is done with "make latest".


NOTE WELL
---------

Any submission to the [IETF](http://www.ietf.org/) intended by the Contributor
for publication as all or part of an IETF Internet-Draft or RFC and any
statement made within the context of an IETF activity is considered an "IETF
Contribution". Such statements include oral statements in IETF sessions, as
well as written and electronic communications made at any time or place, which
are addressed to:

 * The IETF plenary session
 * The IESG, or any member thereof on behalf of the IESG
 * Any IETF mailing list, including the IETF list itself, any working group 
   or design team list, or any other list functioning under IETF auspices
 * Any IETF working group or portion thereof
 * Any Birds of a Feather (BOF) session
 * The IAB or any member thereof on behalf of the IAB
 * The RFC Editor or the Internet-Drafts function
 * All IETF Contributions are subject to the rules of 
   [RFC 5378](http://tools.ietf.org/html/rfc5378) and 
   [RFC 3979](http://tools.ietf.org/html/rfc3979) 
   (updated by [RFC 4879](http://tools.ietf.org/html/rfc4879)).

Statements made outside of an IETF session, mailing list or other function,
that are clearly not intended to be input to an IETF activity, group or
function, are not IETF Contributions in the context of this notice.

Please consult [RFC 5378](http://tools.ietf.org/html/rfc5378) and [RFC 
3979](http://tools.ietf.org/html/rfc3979) for details.

A participant in any IETF activity is deemed to accept all IETF rules of
process, as documented in Best Current Practices RFCs and IESG Statements.

A participant in any IETF activity acknowledges that written, audio and video
records of meetings may be made and may be available to the public.

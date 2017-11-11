# Web Platform Working Group

## Contributing to the microdata spec.

Please feel free to file issues against the specification, or to propose a fix for an existing issue. 
The preferred way to do this is through raising github issues and making github pull requests.
If you are uncomfortable with that process, you may also send comments by email to public-webapps@w3.org, 
with a subject that **begins** with the text `[microdata] `. All email comments will be available in a
[public archive](https://lists.w3.org/Archives/Public/public-webapps).

If you are not a participant in the [W3C Web Platform Working Group](https://w3.org/WebPlatformWG) 
your contributions may be marked as having "IPR issues". If the contributions are purely editorial,
this will be handled by the editors, but if they involve changes to conformance, such as new features,
they will not be accepted without a formal agreement to W3C's intellectual property policies (see below for more) 

### Issues
Issues should describe the problem. Proposals to fix it can be made as comments on the issue,
but should include known implementation of the proposal.

If you want to make a Pull request for simple editorial corrections, it is not necessary to raise an issue.

### Pull requests
The best way to propose a fix is to make a branch,
commit your changes to the branch and then create a Pull Request. Pull Requests should inclue the following information:

; Does it fix a known issue? 
: If so, add `Fix #333, #222` in a line by itself in a comment, which will close the issue
; Does it relate to a known issue? 
: If so, add a comment like `see also #444, #111`, and preferably an explanation of how it relates.
: If not, and it is more than merely editorial, please open an issue
; Known implementation of the change
; Links to tests for any changed behaviour
: Ideally these will be in the form of Web-platform-tests but there are things that can require a manual test.
; Acknowledgements and changelog updates
: If the issue has been worked on by somebody who is not acknowledged already in the acknolwedgements section,
 please add their name
: If the change is substantive, i.e. affects conformance, or a significant editorial one, please note it in the changes section

## Licensing and IPR

Contributions to this repository are expected to become part of a Recommendation governed by the
[W3C Patent Policy](http://www.w3.org/Consortium/Patent-Policy-20040205/) and
[W3C Software and Document License](http://www.w3.org/Consortium/Legal/copyright-software). To make substantive contributions to specifications, you must either participate
in the relevant W3C Working Group or make a non-member patent licensing commitment.

If you are not the only contributor to a proposal resulting in a pull request, please identify all
contributors in the pull request comment.

To add a contributor (other than yourself, that's automatic), mark them one per line as follows:

```
+@github_username
```

If you added a contributor by mistake in an earlier comment, you can remove them in a comment with:

```
-@github_username
```

# www.hathat.fi

Repository for [www.hathat.fi](http://www.hathat.fi) site. Very simple site with only an index page and some contact information.

## Hosting & Deployment

Site is hosted at Google Firebase hosting to get SSL cert as easily as possible. Deployment is automated with Google Cloud Container
Builder; see cloudbuild.yaml for details.

To deploy manually run `firebase deploy`.
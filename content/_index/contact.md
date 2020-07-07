+++
fragment = "contact"
disabled = true
date = "2017-09-10"
weight = 1100
#background = "light"
form_name = "contact"

title = "Kontakt"
subtitle  = "Scheiben Sie mir oder rufen mich direkt an. Telefon 02964 693"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/mlewkkwb" #default: formspree.io
email = "mail@example.com"
button = "Send Button" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = " Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Telefon *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Nachricht *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++

---
title : "SAY HELLO!"
bg_image: "images/backgrounds/contact-us-bg.jpg"
form_action: "https://formspree.io/f/moqrkeop" # works with https://formspree
method: "POST"
name: "Name"
email: "Email"
message: "Message"
submit: "Submit"

<script src="https://formspree.io/js/formbutton-v1.min.js" defer></script>
<script>
  /* paste this line in verbatim */
  window.formbutton=window.formbutton||function(){(formbutton.q=formbutton.q||[]).push(arguments)};
  /* customize formbutton below*/     
  formbutton("create", {
    action: "https://formspree.io/f/moqrkeop",
    title: "How can we help?",
    fields: [
      { 
        type: "email", 
        label: "Email:", 
        name: "email",
        required: true,
        placeholder: "your@email.com"
      },
      {
        type: "textarea",
        label: "Message:",
        name: "message",
        placeholder: "What's on your mind?",
      },
      { type: "submit" }      
    ],
    styles: {
      title: {
        backgroundColor: "gray"
      },
      button: {
        backgroundColor: "gray"
      }
    }
  });
</script>
# custom style
custom_class: "" 
custom_attributes: "" 
custom_css: ""
---
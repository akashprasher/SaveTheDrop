# Save The Drop

A website about conservating water and it's importance in our life.

## Technology Used :
* HTML
* CSS
* BOOTSTRAP

Designed with HTML, CSS and Bootstrap. A donation button is included which is integrated with *[Paypal](https://www.paypal.com)* through which payment to a specific account can be done.This Website is Responsive for every screen resolution.

## Paypal Integration :
        <a class="donate" target="_blank" href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WUQZADSP83XSC&source=url"><img src="https://www.paypalobjects.com/en_GB/i/btn/btn_donate_SM.gif" alt=""></a>
        //URL Generated via https://www.paypal.com



## "Join Us" Form using [Google Forms](https://www.google.com/forms/about/)
All response using this form are stored in the [Google Forms](https://www.google.com/forms/about/) 

###### Attributes we need to customize the form
        <input type="text" name="entry.648625325" placeholder="John" required>
        
   * "entry.648625325" is the name for the first name  and this value can be found at the [Original Google form](https://docs.google.com/forms/d/e/1FAIpQLSffhL61XBXROZO6YJKoOMKrJfDwyKUbYTLE1dP81j7DamqJGg/viewform)
   
         <input type="text" class="quantumWizTextinputPaperinputInput exportInput" jsname="YPqjbf" autocomplete="off" tabindex="0" aria-label="First Name" aria-describedby="i.desc.2057767176 i.err.2057767176" name="entry.648625325" value="" required="" dir="auto" data-initial-dir="auto" data-initial-value="" aria-invalid="true">
   
   * We need to inspect the source code and find the location of the particular input (For Example Name or any other value)

   * We have to insert the value of *"action"* in *"form"* Attribute as the link of the form.
        
         <form action="https://docs.google.com/forms/d/e/1FAIpQLSffhL61XBXROZO6YJKoOMKrJfDwyKUbYTLE1dP81j7DamqJGg/formResponse" method="POST" target="hidden_iframe" onsubmit="submitted=true;">
         
   * 

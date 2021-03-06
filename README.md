# Useful codes

• convert_ascii_for_data-fixtures.html
-------------
If you want to set ISO Language Codes and the name in the corresponding language, because of not all characters are supported in the database back up or return, you must encode language native name into ASCII before use them.

This JS function shows the native name of the language of the ISO 639-1 list in ASCII and writes the code to copy / paste from the HTML view to a DataFixture file (result https://git.io/JI2rD).

Than to recover text : 
- Use html_entity_decode('...', ENT_QUOTES, 'UTF-8') into your PHP function whitch is getting value.  
- Or use jQuery, for example:  
$('body').find('.decode').each(function(){  
  $(this).html($(this).html($(this).html()).text()).text()  
})

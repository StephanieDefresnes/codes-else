# Useful codes

• convert_ascii_for_data-fixtures.html
-------------
JS functions used to show language native name of ISO 639-1 list in ASCII for copying/pasting lines from HTML view to a DataFixture file (result https://git.io/JI2rD).

Than to recover text : 
- Use html_entity_decode('...', ENT_QUOTES, 'UTF-8') into your PHP function whitch is getting value.  
- Or use jQuery, for example:  
$('body').find('.decode').each(function(){  
  $(this).html($(this).html($(this).html()).text()).text()  
})

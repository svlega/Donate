To create the DONATE page

1. Create a cms page for showing the donate options in CMS->Manage Pages
{{block type="catalog/product_view" product_id="3" default_price="30" template="donate/donate.phtml" }}

2.Add the css file by modifying the layout in the 'Design' tab -> 'Layout update XML'

<reference name="head">
	<action method="addItem"><type>skin_css</type><name>css/donate.css</name></action>
</reference>	
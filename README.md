# wordpress-essential-addons-blog-ement-equal-height
This Is the CSS Code For Elemnotor Addon's { Post Grid } Element.This Code Will Make equal Height for all the blog Post's Card.    https://essential-addons.com/elementor/post-grid/

For Run THis Code add A class Into Advanced Tab In Elementor ( Just Like Shown in Image)![image](https://github.com/qaisar6553/wordpress-essential-addons-blog-ement-equal-height/assets/111532224/7e095c0f-a0a1-4f78-9c7f-10c6a4a238ea).



.blog-template .eael-grid-post-excerpt a{
    width: fit-content;
}
.blog-template .eael-post-grid
{
    display: grid;
    grid-template-columns: auto auto auto;
}
.blog-template article.eael-grid-post.eael-post-grid-column
{
    width: 100% !important
}
.eael-grid-post-holder
{
    height: 100%;
}
.eael-grid-post-holder-inner
{
    display: grid;
    display: grid;
  grid-template-columns: auto;
}
@media only screen and (max-width: 600px) {
.blog-template .eael-post-grid
{
    display: grid;
    grid-template-columns: auto auto auto;
}
}



<strong>Withiout Code</strong> 
![image](https://github.com/qaisar6553/wordpress-essential-addons-blog-ement-equal-height/assets/111532224/52efc0c0-74ba-42b1-8497-75c3b25a6067)
<strong>With Code</strong> 
![image](https://github.com/qaisar6553/wordpress-essential-addons-blog-ement-equal-height/assets/111532224/d2431cda-926a-4693-85d4-df0cf638d756)

# Vue-JS--challenge-2

Attribute binding in Vue2:
-	If we want to bind an attribute, i.e. display the attribute from JS to html : use v-bind
-	V-bind:attribute_name=”expression” – in html file
-	V-bind is dynamically binding of attribute
-	Eg: v-bind:src=”image” in html file & in js file inside the vue instance: image=”url of image”
-	Shorthand of v-bind:src=”image” is :src=”image”
-	Data binding- the host of the data is linked to the target of the data. In this case, our data is hosted by the data property of our Vue instance. And we want to target that data from our src.

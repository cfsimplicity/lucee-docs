Prefix by which to access the imported custom CFML or JSP tags.

If you import a CFML custom tag directory and specify an empty value, "", for this attribute, you can call the custom tags without using a prefix. 

You must specify and use a prefix for a JSP tag library.

Example usage after import:

```cfml
<my:customTag attribute="value">
```
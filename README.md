# Intellij Custom Templates

Intellij comes with a number of 'live templates' to speed up development. They allow us to insert standard statements via abbreviations. Documentation explaining live templates in further detail can be found [here](https://www.jetbrains.com/help/idea/2017.1/live-templates.html)

The custom.xml file in this repo contains some custom templates that I use frequently.

I have listed the default live templates that come with Intellij for Java and Groovy file below.

#Maven
dep – Inserts <dependency/>
pl – Inserts <plugin/>
repo – Inserts <repo/>

#Iterations
fori – creates iteration loop
itar – iterates elements of array
itco – iterates elements of java.util.Collection
iter – iterates Iterable
itit – iterates java.util.Iterator
itli – iterates elements of java.util.List

#Other
ifn – Inserts “if null” statement
inn – Inserts “if not null” statement
inst – Checks object type with instanceof and down-casts it
lazy – Performs lazy initialization

#Plain
psf – public static final
psfi – public static final int
psfs – public static final String
thr – throw new
psvm - Inserts a public static void main method
geti - Inserted get instance method.
st - Inserts a String declaration.
wrapIt - Inserts gradle wrapper task block

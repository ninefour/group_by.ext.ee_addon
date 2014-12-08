Group By Extension for ExpressionEngine
=====================

This simple extension adds SQL style 'group by' support to the {channel:entries} tag pair. Pass a 'groupby' parameter in your channel entries loops (currently only supports standard entry fields and custom fields by id; 'field_id_1')

<pre>
{exp:channel:entries channel="advertising" groupby="field_id_1"}
{title}
{/exp:channel:entries}
</pre>

In the example above this is being used to output banner ads which are related (with field_id_1) to a sponsor and ensure that only 1 ad from each sponsor is shown.

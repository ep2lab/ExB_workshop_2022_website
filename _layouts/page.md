<!doctype html>
<html>
    {% include common/head.html %}
    <body>
        {% include common/googleanalytics.html %}
        {% include common/logonav.html %}
        <div id="main">
            {{ content }}
        </div>
        {% include common/footer.html %}
        {% include common/endscripts.html %}
    </body>
</html>

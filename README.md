# My Awesome Book

This file serves as your book's preface, a great place to describe your book's content and ideas.

{% chart %}
{
    // NOT need to specified `bindto` here
    data: {
        type: 'bar',
        columns: [
            ['data1', 30, 200, 100, 400, 150, 250],
            ['data2', 50, 20, 10, 40, 15, 25]
        ],
        axes: {
            data2: 'y2'
        }
    },
    axis: {
        y2: {
            show: true
        }
    }
}
{% endchart %}





---
identifier: hardware-standard-medallion
name: 3/4 inch Saw Medallion
description: "3/4 inch standard medallion comes with recessed medallion, two spur washers, and 1/2 inch split nut."
price: "10.00"
image: /assets/images/saw-medallion.jpg
---
<form target="paypal" action="https://www.paypal.com/cgi-bin/webscr" method="post">
    <!-- Identify your business so that you can collect the payments. -->
    <input type="hidden" name="business" value="ian@sierranvtool.com">

    <!-- Specify an Add to Cart button. -->
    <input type="hidden" name="cmd" value="_cart">
    <input type="hidden" name="add" value="1">

    <!-- Specify details about the item that buyers will purchase. -->
    <input type="hidden" name="item_name" value="3/4 inch Saw Medallion">
    <input type="hidden" name="amount" value="10.00">
    <input type="hidden" name="currency_code" value="USD">

    <div class="product-options">
        <!-- Provide a drop-down menu option field. -->
        <input type="hidden" name="on0" value="Style">
        <label for="os0">Medallion Style</label>
        <select name="os0" id="os0">
            <option value="">-- Select a style --</option>
            <option value="Flat">Flat</option>
            <option value="Recessed" selected="selected">Recessed</option>
        </select>
    </div>

    <!-- Display the payment button. -->
    <button class="product-button">Add to Cart</button>
</form>

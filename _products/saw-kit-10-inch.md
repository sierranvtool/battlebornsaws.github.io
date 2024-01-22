---
identifier: saw-kit-10-inch
name: "10 inch Dovetail Saw Kit"
description: "Standard back with 0.020 inch slot and plate.  10 inch dovetail saws have a 2 inch depth of cut.  Either 13ppi or 15ppi rip cut toothline."
price: "55.00"
image: /assets/images/saw-kit-no-medallion.jpg
---
<form target="paypal" action="https://www.paypal.com/cgi-bin/webscr" method="post">
    <!-- Identify your business so that you can collect the payments. -->
    <input type="hidden" name="business" value="ian@sierranvtool.com">

    <!-- Specify an Add to Cart button. -->
    <input type="hidden" name="cmd" value="_cart">
    <input type="hidden" name="add" value="1">

    <!-- Specify details about the item that buyers will purchase. -->
    <input type="hidden" name="item_name" value="10 inch Dovetail Saw Kit">
    <input type="hidden" name="amount" value="55.00">
    <input type="hidden" name="currency_code" value="USD">

    <div class="product-options">
        <!-- Provide a drop-down menu option field. -->
        <input type="hidden" name="on0" value="Toothline">
        <label for="os0">Toothline</label>
        <select name="os0" id="os0">
            <option value="">-- Select a size --</option>
            <option value="13ppi rip" selected="selected">13ppi rip</option>
            <option value="15ppi rip">15 ppi rip</option>
        </select>
    </div>

    <!-- Display the payment button. -->
    <button class="product-button">Add to Cart</button>
</form>

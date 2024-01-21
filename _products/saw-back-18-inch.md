---
identifier: saw-back-18-inch
name: 18" Saw Back
description: "All saw backs are 3/4 inch tall and 1/4 inch wide.  Choice of slot: .015, .018, .020, or .025 inches.  Optional 5/8 inch height."
price: "19.00"
image: /assets/images/saw-back.jpg
---
<form target="paypal" action="https://www.paypal.com/cgi-bin/webscr" method="post">
    <!-- Identify your business so that you can collect the payments. -->
    <input type="hidden" name="business" value="ian@sierranvtool.com">

    <!-- Specify an Add to Cart button. -->
    <input type="hidden" name="cmd" value="_cart">
    <input type="hidden" name="add" value="1">

    <!-- Specify details about the item that buyers will purchase. -->
    <input type="hidden" name="item_name" value="18 inch Saw Back">
    <input type="hidden" name="currency_code" value="USD">

    <div class="product-options">
        <!-- Provide a drop-down menu option field. -->
        <input type="hidden" name="on0" value="Slot Size">
        <label for="os0">Slot Size</label>
        <select name="os0" id="os0">
            <option value="">-- Select a size --</option>
            <option value=".015 in">0.015"</option>
            <option value=".018 in">0.015"</option>
            <option value=".020 in" selected="selected">0.020"</option>
            <option value=".025 in">0.020"</option>
        </select>

        <!-- Provide a drop-down menu option field with prices. -->
        <input type="hidden" name="on1" value="Height">
        <label for="os1">Height</label>
        <select name="os1" id="os1">
            <option value="">-- Select a height --</option>
            <option value="3/4 inch">3/4 inch</option>
            <option value="5/8 inch">5/8 inch (+ $1.00)</option>
        </select>

        <input type="hidden" name="option_index" value="1">
        <input type="hidden" name="option_select0" value="3/4">
        <input type="hidden" name="option_amount0" value="19.00">
        <input type="hidden" name="option_select1" value="5/8">
        <input type="hidden" name="option_amount1" value="20.00">
    </div>

    <!-- Display the payment button. -->
    <button class="product-button">Add to Cart</button>
</form>

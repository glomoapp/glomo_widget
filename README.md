# Glomo Money Widget

Powerful, Intuitive and easy to use
Glomo Money is build to assist you in managing your day to day financial transactions from the palm of your hand, wherever you are. Glomo money enables you to handle

- Bill payments; electricity, water, TV subscriptions
- Merchant payments; Supermarkets, vendors, service providers
- Bank Transfers; from bank to Glomo and vice versa
- Internal & External transfers; between Glomo account holders and from an account holder to a non-account holder


## Requirements

```html
<script src="src/jquery-1.7.2.min.js"></script>
<script src="src/glomo-widget.min.js"></script>
```
    OR

 ```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="http://payment.widget.glomoapp.com/assets/js/glomo-widget.min.js"></script>
```

## Installation

```html
 $(document).ready(function () {
    $("#widget").GlomoPay({
        setServiceId: "",
        setServiceName: "",
        setPaymentRef: "",
        setAmount: "",
        setLang: "",
        setLogoUrl: "",
        setLabel: "",
        setCallbackUrl: "",
        
    });
})
```

## How To Use
once you have finished the installation place the following code where you want to see the payment button appear

```html
<div id="widget"></div>
```

![screenshot](/pay.PNG)

Supported languages are restricted to the following:

| Language             | Code  |
|----------------------|-------|
| English (default)    | en    |
| French               | fr    |
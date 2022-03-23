# Web-DEv-II-Javascript-Ass
Weru Winrose Web Development II Javascript Assignment


function billingFunc(){
		if (document.getElementById('same').checked){
     var shippingName =  document.getElementById('shippingName').value;
      var shippingZip = document.getElementById('shippingZip').value;
      
     document.getElementById('billingName').value = shippingName;
      document.getElementById('billingZip').value = shippingZip;
     
		}
		else{ 
			document.getElementById('billingName').value = "";
			document.getElementById('billingZip').value = "";
		}
}

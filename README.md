Query to Activate the Discount Function


mutation { <br>
  discountAutomaticAppCreate(  <br>
    automaticAppDiscount: {  <br>
      title: "Group Discounts"  <br>
      functionHandle: "discount-function-setting"  <br>
      startsAt: "2025-01-01T00:00:00"  <br>
      discountClasses: [ORDER]  <br>
      combinesWith: {  <br>
        orderDiscounts: true  <br>
        productDiscounts: true  <br>
        shippingDiscounts: true  <br>
      }  <br>
    }  <br>
  ) {  <br>
    automaticAppDiscount {  <br>
      discountId  <br>
      title  <br>
      status  <br>
      appDiscountType {  <br>
        appKey  <br>
        functionId  <br>
      }  <br>
    }  <br>
    userErrors {  <br>
      field  <br>
      message  <br>
    }  <br>
  }  <br>
}  <br>


<img width="1414" height="735" alt="Screenshot 2026-01-02 at 12 55 52 PM" src="https://github.com/user-attachments/assets/023e7d8e-718a-46f3-abb7-fdf51a5219b2" />

<img width="1198" height="687" alt="Screenshot 2026-01-02 at 12 56 10 PM" src="https://github.com/user-attachments/assets/763ba674-db01-419a-9213-698297ca195b" />

<img width="680" height="691" alt="Screenshot 2026-01-02 at 12 56 27 PM" src="https://github.com/user-attachments/assets/1715330b-3fca-44c2-9cc6-66adfedea442" />

<img width="775" height="548" alt="Screenshot 2026-01-02 at 12 56 49 PM" src="https://github.com/user-attachments/assets/757ccb53-1f4f-472e-8e9a-1793113e6638" />

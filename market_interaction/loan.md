> :arrow_left: [back to menu](../README.md)

# **Loan**

## **TL;DR**

An NFT owner creates a loan proposal with a lot of one or more copies of the NFT as collateral, indicating the Reef amount of the loan, the duration of the loan and the Reef amount paid as interest to the lender. A user can fund the loan. If the borrower does not pay back the principal plus the interest offered, the lender gets ownership of all the copies of the NFT.

<br>

## **How it works for a borrower**

You can create a loan proposal using as collateral any NFT you have on your **[profile's Available section](https://sqwid.app/profile?tab=Available)**, selecting an NFT and clicking on the **Create Loan Proposal** button.

<p align="center">
  <img height="40" src="./images/loan_create_button.png">
</p>

You will be prompted with a modal window that will ask you for four input data:

-   **Loan Amount**: Amount you want to borrow, in Reef.
-   **Payback Fee**: Amount to be paid to the lender as interests for the loan, in Reef.
-   **Number of Copies**: Number of copies of the NFT that will offer as collateral for the loan.
-   **Duration**: The duration of the loan, in minutes.

You can also see the value of the **service fee**. This is the amount that will be charged at the moment of receiving the loan, in case it is funded.

<p align="center">
  <img width="350" src="./images/loan_create_modal.png">
</p>

When you create the loan proposal you don't pay any fee (you just pay the gas for the transaction).

If the loan proposal is funded, at the moment of the funding a service fee will be subtracted from the total amount, so you receive the net amount. Also, the deadline will be calculated, adding the duration of the loan to the current time.

_E.g._

```
You create a loan proposal with the following parameters:
 - Loan amount: 100,000 Reef
 - Payback fee: 2,000 Reef
 - Number of copies: 10
 - Duration: 30 days
 - Service fee: 2.5%

The loan is funded.

A service fee of 2,500 Reef (100,000 Reef * 2.5%) will be charged and you receive 97,500 Reef.

You will have to pay back 102,000 Reef (100,000 as principal plus 2,000 interests) to the lender before the deadline of the loan is reached. The duration of 30 days to pay the loan back starts counting.
```

If you don't pay back the principal plus the payback fee (interests) to the lender by the deadline of the loan, the lender will be able to liquidate the loan by taking ownership of the NFT put as collateral.

You will be able to repay the loan any time before the liquidation is executed in order to recover the NFT put as collateral. You can do so by navitating to your **[profile's Loans section](https://sqwid.app/profile?tab=Loans)**, selecting the collateralized NFT and clicking on the **Repay** button.

<p align="center">
  <img height="40" src="./images/loan_repay_button.png">
</p>

To unlist a loan proposal that has not yet been funded, you can go to your **[profile's Loans section](https://sqwid.app/profile?tab=Loans)**, select the collateralized NFT and click on the **Unlist** button.

<p align="center">
  <img height="40" src="./images/loan_unlist_button.png">
</p>

<br>

## **How it works for a lender**

You can explore all **[Loan proposals](https://sqwid.app/explore/loans)**. If you open the detail page of an item, you can see the detail of the NFT and will find a **Fund** button.

<p align="center">
  <img height="40" src="./images/loan_fund_button.png">
</p>

By funding the loan, you will send the loan amount to the borrower and the duration of the loan will start counting.

If the borroes doesn't pay back the principal plus the payback fee (interests) by the deadline of the loan, you will be able to liquidate the loan by taking ownership of the NFT put as collateral.

To liquidate an expired loan you can go your [profile's Loans section](https://sqwid.app/profile?tab=Loans), select the collateralized NFT and click on the **Liquidate** button.

<p align="center">
  <img height="40" src="./images/loan_liquidate_button.png">
</p>

> :arrow_left: [back to menu](../README.md)
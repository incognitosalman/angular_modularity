# Introducing Modularity in Angular Application

## What is an Angular Module?

In [Angular](https://angular.io/), a module is a mechanism to group different components, directives, pipes and services etc. that are inter-related, in such a way that can be combined with other modules to create an application. 

## About this exercise

Previously we scafolded a new Angular application in which we have integrated 

* Scaffolded the angular application
* [FontAwesome](https://fontawesome.com/) Library for icons
* [Bootstrap](https://getbootstrap.com/) Library for styling buttons
* Bootstrap NavBar component
* Routing for multiple components e.g. (CreateAccountComponent, ManageAccountsComponent, DepositFundsComponent, TransferFundsComponent) for which we have already configured routing. Also we have commented code of links in app.component.html as below :

```html
<!-- <ul>
  <li><a><i class="fas fa-chart-line"></i> Dashboard</a></li>
  <div>
    <li><a [routerLink]="['/transfer-funds']"><i class="fas fa-random"></i> Transfer Funds</a></li>
    <li><a [routerLink]="['/deposit-funds']"><i class="fas fa-money-check-alt"></i>Deposit Funds</a></li>
    <li><a [routerLink]="['/create-account']"><i class="fas fa-user"></i> Create New Account</a></li>
    <li><a [routerLink]="['/manage-accounts']"><i class="fas fa-users"></i> Manage Accounts</a></li>
  </div>
</ul> -->
```
* SideNav having links which are navigating to these pages

In this exercise we are going to split our application into three modules

* Shared module in which we have components which are common to all application (toolbar, sidenav, and dashboard)
* Bank manager module (create account and manage accounts)
* Account holder module (transfer funds and deposit funds) 
* We will implement the lazy loading of these modules in our application


### Step 1: Create Shared Module

### Step 2: Create Bank Manager Module

### Step 3: Create Account Holder Module

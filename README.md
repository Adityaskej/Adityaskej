<html>
<head>
    <title>SIMPLE BANK</title>
    <h1>SIMPLE BANK</h1>
    <style>
        body {
            background-color: rgb(200, 200, 222);
            font-size: 33px;
            text-align: center;
    </style>        
<div id="account-area">
    <div class="container">
        <div class="row">
            <div class="col-lg-4 mb-3">
                <div class="deposit status">
                    <h5>Deposit</h5>
                    <h2>$ <span id="current-deposit">00</span></h2>
                </div>
            </div>
            
            <div class="col-lg-4 mb-3">
                <div class="withdraw status">
                    <h5>Withdraw</h5>
                    <h2>$ <span id="current-withdraw">00</span></h2>
                </div>
            </div>
            
            <div class="col-lg-4 mb-3">
                <div class="balance status">
                    <h5>Balance</h5>
                    <h2>$ <span id="current-balance">1240</span></h2>
                </div>
             </div>
        </div>
    </div>

    <div class="container">
        <div class="row">
            <div class="col-lg-6">
                <div class="submit-area">
                    <h4>Deposit Amount</h4>
                    <input id="deposit-amount" type="text" class="form-control" placeholder="Enter deposit amount"><br>
                    <button id="deposit-btn" class="btn btn-success">Deposit</button>
                </div>
            </div>
            
            <div class="col-lg-6">
                <div class="submit-area">
                    <h4>Withdraw Amount</h4>
                    <input id="withdraw-amount" type="text" class="form-control" placeholder="Enter withdraw amount"><br>
                    <button id="withdraw-btn" class="btn btn-success">Withdraw</button>
                </div>
            </div>
        </div>
    </div>
</div>

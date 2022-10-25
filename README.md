.mea-easy-launch-app .vld-overlay .vld-icon svg {
  fill: white;
}

.mea-easy-launch-app {
  background: linear-gradient(30deg, rgba(1, 143, 219, 1) 0%, rgba(249, 95, 3, 1) 95%);
  border-radius: 15px;
  color: red;
  font-family: Helvetica, sans-serif !important;
  height: 100%;
  position: absolute;
  width: 100%;
}

.mea-easy-launch-container {
  display: flex;
  flex-direction: column;
  font-size: 20px;
  height: 100%;
}

.mea-easy-launch-container .mea-data:nth-child(1) { order: 2; }
.mea-easy-launch-container .mea-data:nth-child(2) { order: 4; }
.mea-easy-launch-container .mea-data:nth-child(3) { order: 3; }
.mea-easy-launch-container .mea-data:nth-child(4) { order: 1; }

.mea-cvv-result {
  padding-left: 20px;
  padding-top: 15px;
  text-align: left;
}

.mea-cardholder-result {
  margin-top: auto;
  padding-bottom: 15px;
  padding-left: 20px;
}

.mea-pan-result {
  padding-bottom: 10px;
  padding-top: 45px;
}

.mea-expiry-result,
.mea-pan-result {
  text-align: center;
}

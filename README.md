<!DOCTYPE html>
    gap: 20px;
  }
  .pet-card {
    cursor: pointer;
    border: 3px solid transparent;
    border-radius: 15px;
    padding: 10px;
    transition: border-color 0.3s;
    user-select: none;
  }
  .pet-card.selected {
    border-color: #00cc66;
    box-shadow: 0 0 10px #00cc66;
  }
  .pet-card img {
    width: 120px;
    border-radius: 12px;
  }
  .button {
    background-color: #00cc66;
    border: none;
    color: white;
    font-size: 18px;
    padding: 15px 40px;
    border-radius: 12px;
    cursor: pointer;
    margin-top: 25px;
    transition: background-color 0.3s;
  }
  .button:hover {
    background-color: #00b359;
  }
  .inventory {
    margin-top: 40px;
    text-align: left;
  }
  .inventory h2 {
    color: #0078D7;
  }
  .inventory-list {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
  }
  .inventory-item {
    border: 2px solid #0078D7;
    border-radius: 12px;
    padding: 10px;
    width: 120px;
    text-align: center;
  }
  .inventory-item img {
    width: 100px;
    border-radius: 10px;
  }
  /* Login popup */
  .login-popup {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.7);
    justify-content: center;
    align-items: center;
    z-index: 1000;
  }
  .login-box {
    background: white;
    padding: 30px;
    border-radius: 15px;
    width: 320px;
    box-shadow: 0 6p

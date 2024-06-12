# Project Title : Barcode Reader

# Introduction 
  This project helps to Scan barcode,add to cart, gets total cost.

# TechStack 
  - FastApi
  - PostgreSQL
  - Streamlit

# Features 
  - Scan Bar code
  - Add to Cart
  - Gets Total cost of items in Cart

# Run code 
  ## Install necassary modules 
     - pip install -r requirements.txt
  ## Run Backend code 
     - uvicorn main:app --reload
  ## Run Frontend code
     - streamlit run UI.py
     


# To insert values to items tabel

-INSERT INTO public."Items"(
"Item_Id", "ItemName", "Price")
VALUES ('Ab1234', 'Apple', 120000);

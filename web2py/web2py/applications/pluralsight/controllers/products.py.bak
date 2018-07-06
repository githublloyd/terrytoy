# -*- coding: utf-8 -*-
# try something like
def index(): return dict(message="hello from products.py")

def admin_view():
    sql = "SELECT products.id, products.product_name, orders.order_price, orders.order_date"
    sql = sql + "FROM products inner join orders on products.id = orders.product_id;"
    rows = db.executesql(sql)
    return locals()

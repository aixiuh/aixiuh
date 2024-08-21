select count(1) from (
select distinct tp_order_id,user_id,brand,sub_channel_name from
table)和
select count(distinct tp_order_id,user_id,brand,sub_channel_name) from
table的结果不一样

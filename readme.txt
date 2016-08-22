主要负责拼接生成sql语句 
使用规则请参考medoo类库 
由于目前公司部分项目需要单独分离出来此功能

$sql = $data->select("modoer_areacode","*",array("ORDER"=>"areasort DESC"));
print_r($sql);exit;
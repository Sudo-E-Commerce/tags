# Hướng dẫn sử dụng Sudo Tag #

## Cài đặt để sử dụng ##

## Cấu hình tại Menu ##

	[
    	'type' 		=> 'single',
		'name' 		=> 'Quản lý Tags',
		'icon' 		=> 'fas fa-tags',
		'route' 	=> 'admin.tags.index',
		'role'		=> 'tags_index'
	],

## Cấu hình tại Module ##
	
	'tags' => [
		'name' 			=> 'Tags',
		'permision' 	=> [
			[ 'type' => 'index', 'name' => 'Truy cập' ],
			[ 'type' => 'create', 'name' => 'Thêm' ],
			[ 'type' => 'edit', 'name' => 'Sửa' ],
			[ 'type' => 'restore', 'name' => 'Lấy lại' ],
			[ 'type' => 'delete', 'name' => 'Xóa' ],
		],
	],

## Publish ##

## Sử dụng ##

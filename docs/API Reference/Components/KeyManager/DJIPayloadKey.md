<div class="article"><h1 ><font color="#AAA">class </font>PayloadKey</h1></div>

~~~java
 class PayloadKey extends DJIKey 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.keysdk</td></tr><tr valign="top"><td width=15%><font color="#999"><i>Inherits From:</i></td><td width=85%><font color="#999"><code><a href="/Components/KeyManager/DJIKey.html#djikey">DJIKey</a></code></td></tr></table></html>



##### Description:



<font color="#666"><code><a href="/Components/KeyManager/DJIPayloadKey.html#djipayloadkey">PayloadKey</a></code> provides dedicated access to Flight  controller attributes.



##### Inherited Methods:



##### Class Keys:

<html><table class="key_table"><tr><td colspan=2><a href="#payloadkey_config_interface_payload_widgets_key"></a><p class="key_table_key_string key_table_key_first_row">CONFIG_INTERFACE_PAYLOAD_WIDGETS</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code><a href="/Components/Payload/DJIPayload_PayloadWidget.html#djipayload_payloadwidget">PayloadWidget</a>[]</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_serial_number_key"></a><p class="key_table_key_string key_table_key_row">SERIAL_NUMBER</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">GET</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>String</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_payload_model_key"></a><p class="key_table_key_string key_table_key_row">PAYLOAD_MODEL</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code><a href="/Components/Payload/DJIPayload.html#djipayload_djipayloadproductphase">PayloadProductPhase</a></code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_firmware_version_key"></a><p class="key_table_key_string key_table_key_row">FIRMWARE_VERSION</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">GET</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>String</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_send_data_to_payload_key"></a><p class="key_table_key_string key_table_key_row">SEND_DATA_TO_PAYLOAD</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">ACTION</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>byte[]</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_is_accessory_connect_key"></a><p class="key_table_key_string key_table_key_row">IS_ACCESSORY_CONNECT</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>Boolean</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_connection_key"></a><p class="key_table_key_string key_table_key_row">CONNECTION</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>Boolean</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_payload_widgets_list_info_key"></a><p class="key_table_key_string key_table_key_row">PAYLOAD_WIDGETS_LIST_INFO</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>PayloadFileInfo[]</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_get_widget_key"></a><p class="key_table_key_string key_table_key_row">GET_WIDGET</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">ACTION</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>-</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_get_input_text_param_key"></a><p class="key_table_key_string key_table_key_row">GET_INPUT_TEXT_PARAM</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">GET</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>PayloadTextParam</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_get_data_from_payload_key"></a><p class="key_table_key_string key_table_key_row">GET_DATA_FROM_PAYLOAD</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>byte[]</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_get_upstream_bandwidth_key"></a><p class="key_table_key_string key_table_key_row">GET_UPSTREAM_BANDWIDTH</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">GET</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>Float</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_configure_widget_value_key"></a><p class="key_table_key_string key_table_key_row">CONFIGURE_WIDGET_VALUE</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">ACTION</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>-</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_main_interface_payload_widgets_key"></a><p class="key_table_key_string key_table_key_row">MAIN_INTERFACE_PAYLOAD_WIDGETS</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code><a href="/Components/Payload/DJIPayload_PayloadWidget.html#djipayload_payloadwidget">PayloadWidget</a>[]</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_hint_message_key"></a><p class="key_table_key_string key_table_key_row">HINT_MESSAGE</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>String</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_payload_product_name_key"></a><p class="key_table_key_string key_table_key_row">PAYLOAD_PRODUCT_NAME</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code>String</code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr><tr><td colspan=2><a href="#payloadkey_payload_device_type_key"></a><p class="key_table_key_string key_table_key_row">PAYLOAD_DEVICE_TYPE</p></td></tr></tr><td><p class="key_table_title_string">Access:</p></td><td><p class="key_table_type_string">PUSH</p></td></tr><tr class="key_table_doc_row"><td><p class="key_table_title_string">Type:</p></td><td><p class="key_table_type_string"><code><a href="/Components/Payload/DJIPayload.html#djipayload_djipayloaddevicetype">PayloadDeviceType</a></code></p></td></tr><td><p class="key_table_title_string">API:</p></td><td><p class="key_table_type_string">-</p></td></tr></table></html>
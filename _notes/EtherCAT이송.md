 EtherCAT통신은 1ms 마다 데이터를 주고 받는 통신입니다.
 따라서 EtherCAT을 사용하여 장치나 장비를 이송하는 경우 1ms 마다 Command Position을 재설정하여 전송하게 됩니다.
 예를 들어서 1ms 마다 10 이라는 거리를 이동하는 장치가 1000이라는 거리를 이동해야 되는 상황이라고 하겠습니다.
 EtherCAT Master에서는 첫 Command Position 은 10~ 11 정도의 Command Position을 보내고 또 다시 1ms 뒤에는 21~22 정도의 Command Position을 보내게 됩니다. 이런 식으로 마지막 이송에서는 999~1001 정도의 Command Position 전송합니다.




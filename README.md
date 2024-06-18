# 햄스터-S Python API 메뉴얼

<br>

![](https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/fdc0b9f7-03ff-4cc2-90db-08ab1a57dbb5)

<br>

**햄스터-S**사용자들을 위한 [Python API Wiki](https://github.com/RobomationLAB/BeagleAPI_KR/wiki)입니다.


이 문서는 로보메이션의 햄스터-S를 Python으로 프로그래밍하려는 사용자를 위한 라이브러리 API Guide입니다. 

아래 목차에서 **도움말**을 보고싶은 **목차**를 선택하세요.

<br>




<br><br><br><br>


- ### [시작하기에 앞서](https://github.com/RobomationLAB/HamsterSAPI_KR/wiki/시작하기에-앞서)
- ### [초보자를 위한 파이썬 설치 가이드](https://github.com/RobomationLAB/HamsterSAPI_KR/wiki/초보자를-위한-파이썬-설치-가이드)

<br>

# [생성 및 해제]()


<details>
    <summary>
        <a href="">
            햄스터 생성
        </a>
    </summary>

- [HamsterS]()
- [HamsterS(index)]()
- [HamsterS(port_name)]()
- [HamsterS(index, port_name)]()

</details>



<details>
    <summary>
        <a href = "">
        햄스터 해제
    </summary>

- [dispose()]()
- [reset()]()

</details>


<br>




# [바퀴움직임]()

<details>
    <summary>
        <a href = "">
        전진
    </summary>

- [move_forward()]()
- [move_forward(cm)]()
- [move_forward(cm,velocity)]()
- [move_forward_sec(sec)]()
- [move_forward_sec(sec,velocity)]()
- [move_forward_pulse(pulse)]()
- [move_forward_pulse(pulse,velocity)]()

</details>



<details>
    <summary>
        <a href = "">
        후진
    </summary>

- [move_backward()]()
- [move_backward(cm)]()
- [move_backward(cm, velocity)]()
- [move_backward_sec(sec)]()
- [move_backward_sec(sec, velocity)]()
- [move_backward_pulse(pulse)]()
- [move_backward_pulse(pulse, velocity)]()

</details>


<details>
    <summary>
        <a href = "">
        스핀
    </summary>

- [turn_left()]()
- [turn_left(degree)]()
- [turn_left(degree, velocity)]()
- [turn_left_sec(sec)]()
- [turn_left_sec(sec, velocity)]()
- [turn_left_pulse(pulse)]()
- [turn_left_pulse(pulse, velocity)]()
- [turn_right()]()
- [turn_right(degree)]()
- [turn_right(degree, velocity)]()
- [turn_right_sec(sec)]()
- [turn_right_sec(sec, velocity)]()
- [turn_right_pulse(pulse)]()
- [turn_right_pulse(pulse, velocity)]()

</details>


<details>
    <summary>
        <a href = "">
        피봇
    </summary>

- [pivot_left_wheel(degree)]()
- [pivot_left_wheel(degree, velocity)]()
- [pivot_left_wheel_sec(sec)]()
- [pivot_left_wheel_sec(sec, velocity)]()
- [pivot_left_wheel_pulse(pulse)]()
- [pivot_left_wheel_pulse(pulse, velocity)]()
- [pivot_right_wheel(degree)]()
- [pivot_right_wheel(degree, velocity)]()
- [pivot_right_wheel_sec(sec)]()
- [pivot_right_wheel_sec(sec, velocity)]()
- [pivot_right_wheel_pulse(pulse)]()
- [pivot_right_wheel_pulse(pulse, velocity)]()
- [pivot_left_pen(degree)]()
- [pivot_left_pen(degree, velocity)]()
- [pivot_left_pen_sec(sec)]()
- [pivot_left_pen_sec(sec, velocity)]()
- [pivot_left_pen_pulse(pulse)]()
- [pivot_left_pen_pulse(pulse, velocity)]()
- [pivot_right_pen(degree)]()
- [pivot_right_pen(degree, velocity)]()
- [pivot_right_pen_sec(sec)]()
- [pivot_right_pen_sec(sec, velocity)]()
- [pivot_right_pen_pulse(pulse)]()
- [pivot_right_pen_pulse(pulse, velocity)]()


</details>




<details>
    <summary>
        <a href = "">
        라운드턴
    </summary>

- [circle_left(degree,radius)]()
- [circle_left(degree,radius,velocity)]()
- [circle_left_sec(sec,radius)]()
- [circle_left_sec(sec,radius,velocity)]()
- [circle_left_pulse(pulse,radius)]()
- [circle_left_pulse(pulse,radius,velocity)]()
- [circle_right(degree,radius)]()
- [circle_right(degree,radius,velocity)]()
- [circle_right_sec(sec,radius)]()
- [circle_right_sec(sec,radius,velocity)]()
- [circle_right_pulse(pulse,radius)]()
- [circle_right_pulse(pulse,radius,velocity)]()

</details>




<details>
    <summary>
        <a href = "">
        펜홀더활용
    </summary>

- [left_pen_circle_left(degree,radius)]()
- [left_pen_circle_left(degree,radius,velocity)]()
- [left_pen_circle_left_sec(sec,radius)]()
- [left_pen_circle_left_sec(sec,radius,velocity)]()
- [left_pen_circle_left_pulse(pulse,radius)]()
- [left_pen_circle_left_pulse(pulse,radius,velocity)]()
- [left_pen_circle_right(degree,radius)]()
- [left_pen_circle_right(degree,radius,velocity)]()
- [left_pen_circle_right_sec(sec,radius)]()
- [left_pen_circle_right_sec(sec,radius,velocity)]()
- [left_pen_circle_right_pulse(pulse,radius)]()
- [left_pen_circle_right_pulse(pulse,radius,velocity)]()
- [right_pen_circle_left(degree,radius)]()
- [right_pen_circle_left(degree,radius,velocity)]()
- [right_pen_circle_left_sec(sec,radius)]()
- [right_pen_circle_left_sec(sec,radius,velocity)]()
- [right_pen_circle_left_pulse(pulse,radius)]()
- [right_pen_circle_left_pulse(pulse,radius,velocity)]()
- [right_pen_circle_right(degree,radius)]()
- [right_pen_circle_right(degree,radius,velocity)]()
- [right_pen_circle_right_sec(sec,radius)]()
- [right_pen_circle_right_sec(sec,radius,velocity)]()
- [right_pen_circle_right_pulse(pulse,radius)]()
- [right_pen_circle_right_pulse(pulse,radius,velocity)]()

</details>




<details>
    <summary>
        <a href = "">
        바퀴제어
    </summary>

- [wheels(left_velocity, right_velocity)]()
- [left_wheel(velocity)]()
- [stop()]()
- [rotate_wheels()]()
- [rotate_wheels(degree)]()
- [rotate_wheels(degree,velocity)]()
- [rotate_left_wheels()]()
- [rotate_left_wheels(degree)]()
- [rotate_left_wheels(degree,velocity)]()
- [rotate_right_wheels()]()
- [rotate_right_wheels(degree)]()
- [rotate_right_wheels(degree,velocity)]()

</details>




<details>
    <summary>
        <a href = "">
        라인트레이서
    </summary>

- [line_tracer_mode(mode)]()
- [line_left()]()
- [line_right()]()
- [line_both()]()
- [cross_left()]()
- [cross_right()]()
- [cross_forward()]()
- [cross_uturn()]()
- [white_line_left()]()
- [white_line_right()]()
- [white_line_both()]()
- [white_cross_left()]()
- [white_cross_right()]()
- [white_cross_forward()]()
- [white_cross_uturn()]()
- [line_gain(gain)]()
- [line_speed(speed)]()

</details>

<br>

# [LED]()

<details>
    <summary>
        <a href = "">
        RGB [임시제목]
    </summary>

- [rgbs()]()
- [rgbs(red, green, blue)]()
- [rgbs(left_rgb, right_rgb)]()
- [left_rgb(red, green, blue)]()
- [right_rgbs(red, green, blue)]()

</details>

<details>
    <summary>
        <a href = "">
        LED [임시제목]
    </summary>

- [leds()]()
- [leds(red, green, blue)]()
- [leds(left_rgb, right_rgb)]()
- [left_led(red, green, blue)]()
- [right_led(red, green, blue)]()

</details>

<br>

# [소리]()

<details>
    <summary>
        <a href = "">
        주파수 제어
    </summary>

- [buzzer(Hz)]()
- [tempo(bpm)]()

</details>



<details>
    <summary>
        <a href = "">
        NOTE 제어
    </summary>

- [note(pitch)]()
- [note(pitch, beats)]()

</details>





<details>
    <summary>
        <a href = "">
        멜로디 제어
    </summary>

- [sound(sound_id)]()
- [sound(sound_id, repeat)]()
- [sound_until_done(sound_id)]()
- [sound_until_done(sound_id, repeat)]()
- [beep()]()

</details>



<br>



# [입출력모드]()

<details>
    <summary>
        <a href = "">
        입출력설정
    </summary>

- [io_mode_a(mode)]()
- [io_mode_b(mode)]()
- [output_a(value)]()
- [output_b(value)]()
- [input_a()]()
- [input_b()]()
- [voltage_a()]()
- [voltage_b()]()

</details>


<details>
    <summary>
        <a href = "">
        그리퍼
    </summary>

- [open_gripper()]()
- [close_gripper()]()
- [release_gripper()]()

</details>

<br>



# [센서]()

<details>
    <summary>
        <a href = "">
        근접센서
    </summary>

- [left_proximity()]()
- [right_proximity()]()

</details>

<details>
    <summary>
        <a href = "">
        바닥센서
    </summary>

- [left_floor()]()
- [right_floor()]()

</details>

<details>
    <summary>
        <a href = "">
        가속도 감지 센서
    </summary>

- [acceleration_x()]()
- [acceleration_y()]()
- [acceleration_z()]()
- [tilt()]()

</details>

<details>
    <summary>
        <a href = "">
        조도센서, 온도센서, 배터리
    </summary>

- [light()]()
- [temperature()]()
- [battery_state()]()

</details>

<br>





# [전역 함수]()

<details>
    <summary><a href="">
    해제, 다중 작동, 시리얼 포트 출력, 콜백함수</a></summary>

- [dispose()]()
- [parallel(function1, function2, ...)]()
- [parallel((function1, args1), (function2, args2), ...)]()
- [scan()]()
- [set_executable(execute)]()

</details>

<details>
    <summary><a href="">
    대기 함수
    </a></summary>

- [wait(milliseconds)]()
- [wait_until(evaluate)]()
- [wait_until(evaluate, args)]()
- [wait_until_ready()]()

</details>

<details>
    <summary><a href="">조건 함수</a></summary>

- [when_do(when, do)]()
- [when_do(when, do, args)]()

</details>










<br><br>
><a href="https://www.robomation.net" target="_blank">www.robomation.net</a><br>
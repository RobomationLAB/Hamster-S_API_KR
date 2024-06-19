# 햄스터-S Python API 메뉴얼

<br>

![](https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/fdc0b9f7-03ff-4cc2-90db-08ab1a57dbb5)

<br>

**햄스터-S**사용자들을 위한 [Python API Wiki](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki)입니다.


이 문서는 로보메이션의 햄스터-S를 Python으로 프로그래밍하려는 사용자를 위한 라이브러리 API Guide입니다. 

아래 목차에서 **도움말**을 보고싶은 **목차**를 선택하세요.

<br>




<br><br><br><br>

### [시작하기에 앞서](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0%EC%97%90-%EC%95%9E%EC%84%9C)

### [초보자를 위한 파이썬 설치 가이드](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/%EC%B4%88%EB%B3%B4%EC%9E%90%EB%A5%BC-%EC%9C%84%ED%95%9C-%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EC%84%A4%EC%B9%98-%EA%B0%80%EC%9D%B4%EB%93%9C)


### [ 하드웨어 설명 ](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/%ED%95%98%EB%93%9C%EC%9B%A8%EC%96%B4-%EC%84%A4%EB%AA%85)


<br>


# [생성 및 해제](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/%EC%83%9D%EC%84%B1-%EB%B0%8F-%ED%95%B4%EC%A0%9C)


<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/%EC%83%9D%EC%84%B1-%EB%B0%8F-%ED%95%B4%EC%A0%9C#hamster-s-%EC%83%9D%EC%84%B1">
            햄스터-S 생성
        </a>
    </summary>

- [HamsterS](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및해제#hamsters)
- [HamsterS(index)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및해제#hamstersindex)
- [HamsterS(port_name)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및해제#hamstersport_name)
- [HamsterS(index, port_name)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및해제#hamstersindex-port_name)

</details>



<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및-해제#hamster-s-해제">
        햄스터-S 해제
    </summary>

- [dispose()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및-해제#dispose)
- [reset()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/생성-및-해제#reset)



</details>


<br>




# [바퀴움직임](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#전진">
        전진
        </a>
    </summary>

- [move_forward()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forward)
- [move_forward(cm)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forwardcm)
- [move_forward(cm, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forwardcm-velocity)
- [move_forward_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forward_secsec)
- [move_forward_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forward_secsec-velocity)
- [move_forward_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forward_pulsepulse)
- [move_forward_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_forward_pulsepulse-velocity)

</details>





<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#후진">
        후진
        </a>
    </summary>

- [move_backward()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backward)
- [move_backward(cm)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backwardcm)
- [move_backward(cm, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backwardcm-velocity)
- [move_backward_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backward_secsec)
- [move_backward_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backward_secsec-velocity)
- [move_backward_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backward_pulsepulse)
- [move_backward_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#move_backward_pulsepulse-velocity)

</details>



<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#스핀">
        스핀
        </a>
    </summary>

- [turn_left()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_left)
- [turn_left(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_leftdegree)
- [turn_left(degree,  velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_leftdegree-velocity)
- [turn_left_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_left_secsec)
- [turn_left_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_left_secsec-velocity)
- [turn_left_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_left_pulsepulse)
- [turn_left_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_left_pulsepulse-velocity)
- [turn_right()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_right)
- [turn_right(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_rightdegree)
- [turn_right(degree,  velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_rightdegree-velocity)
- [turn_right_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_right_secsec)
- [turn_right_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_right_secsec-velocity)
- [turn_right_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_right_pulsepulse)
- [turn_right_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#turn_right_pulsepulse-velocity)

</details>



<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#피봇">
        피봇
        </a>
    </summary>

- [pivot_left_wheel(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_wheeldegree)
- [pivot_left_wheel(degree,  velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_wheeldegree-velocity)
- [pivot_left_wheel_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_wheel_secsec)
- [pivot_left_wheel_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_wheel_secsec-velocity)
- [pivot_left_wheel_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_wheel_pulsepulse)
- [pivot_left_wheel_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_wheel_pulsepulse-velocity)
- [pivot_right_wheel(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_wheeldegree)
- [pivot_right_wheel(degree,  velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_wheeldegree-velocity)
- [pivot_right_wheel_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_wheel_secsec)
- [pivot_right_wheel_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_wheel_secsec-velocity)
- [pivot_right_wheel_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_wheel_pulsepulse)
- [pivot_right_wheel_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_wheel_pulsepulse-velocity)
- [pivot_left_pen(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_pendegree)
- [pivot_left_pen(degree,  velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_pendegree-velocity)
- [pivot_left_pen_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_pen_secsec)
- [pivot_left_pen_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_pen_secsec-velocity)
- [pivot_left_pen_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_pen_pulsepulse)
- [pivot_left_pen_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_left_pen_pulsepulse-velocity)
- [pivot_right_pen(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_pendegree)
- [pivot_right_pen(degree,  velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_pendegree-velocity)
- [pivot_right_pen_sec(sec)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_pen_secsec)
- [pivot_right_pen_sec(sec, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_pen_secsec-velocity)
- [pivot_right_pen_pulse(pulse)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_pen_pulsepulse)
- [pivot_right_pen_pulse(pulse, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#pivot_right_pen_pulsepulse-velocity)

</details>






<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#라운드-턴">
        라운드턴
        </a>
    </summary>

- [circle_left(degree, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_leftdegree-radius)
- [circle_left(degree, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_leftdegree-radius-velocity)
- [circle_left_sec(sec, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_left_secsec-radius)
- [circle_left_sec(sec, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_left_secsec-radius-velocity)
- [circle_left_pulse(pulse, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_left_pulsepulse-radius)
- [circle_left_pulse(pulse, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_left_pulsepulse-radius-velocity)
- [circle_right(degree, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_rightdegree-radius)
- [circle_right(degree, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_rightdegree-radius-velocity)
- [circle_right_sec(sec, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_right_secsec-radius)
- [circle_right_sec(sec, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_right_secsec-radius-velocity)
- [circle_right_pulse(pulse, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_right_pulsepulse-radius)
- [circle_right_pulse(pulse, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#circle_right_pulsepulse-radius-velocity)

</details>





<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#펜홀더-활용">
        펜홀더활용
        </a>
    </summary>

- [left_pen_circle_left(degree, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_leftdegree-radius)
- [left_pen_circle_left(degree, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_leftdegree-radius-velocity)
- [left_pen_circle_left_sec(sec, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_left_secsec-radius)
- [left_pen_circle_left_sec(sec, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_left_secsec-radius-velocity)
- [left_pen_circle_left_pulse(pulse, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_left_pulsepulse-radius)
- [left_pen_circle_left_pulse(pulse, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_left_pulsepulse-radius-velocity)
- [left_pen_circle_right(degree, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_rightdegree-radius)
- [left_pen_circle_right(degree, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_rightdegree-radius-velocity)
- [left_pen_circle_right_sec(sec, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_right_secsec-radius)
- [left_pen_circle_right_sec(sec, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_right_secsec-radius-velocity)
- [left_pen_circle_right_pulse(pulse, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_right_pulsepulse-radius)
- [left_pen_circle_right_pulse(pulse, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_pen_circle_right_pulsepulse-radius-velocity)
- [right_pen_circle_left(degree, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_leftdegree-radius)
- [right_pen_circle_left(degree, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_leftdegree-radius-velocity)
- [right_pen_circle_left_sec(sec, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_left_secsec-radius)
- [right_pen_circle_left_sec(sec, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_left_secsec-radius-velocity)
- [right_pen_circle_left_pulse(pulse, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_left_pulsepulse-radius)
- [right_pen_circle_left_pulse(pulse, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_left_pulsepulse-radius-velocity)
- [right_pen_circle_right(degree, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_rightdegree-radius)
- [right_pen_circle_right(degree, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_rightdegree-radius-velocity)
- [right_pen_circle_right_sec(sec, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_right_secsec-radius)
- [right_pen_circle_right_sec(sec, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_right_secsec-radius-velocity)
- [right_pen_circle_right_pulse(pulse, radius)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_right_pulsepulse-radius)
- [right_pen_circle_right_pulse(pulse, radius, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#right_pen_circle_right_pulsepulse-radius-velocity)

</details>





<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#바퀴제어">
        바퀴제어
        </a>
    </summary>

- [wheels(left_velocity, right_velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#wheelsleft_velocity-right_velocity)
- [left_wheel(velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#left_wheelvelocity)
- [stop()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#stop)
- [rotate_wheels()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_wheels)
- [rotate_wheels(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_wheelsdegree)
- [rotate_wheels(degree, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_wheelsdegree-velocity)
- [rotate_left_wheels()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_left_wheels)
- [rotate_left_wheels(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_left_wheelsdegree)
- [rotate_left_wheels(degree, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_left_wheelsdegree-velocity)
- [rotate_right_wheels()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_right_wheels)
- [rotate_right_wheels(degree)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_right_wheelsdegree)
- [rotate_right_wheels(degree, velocity)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#rotate_right_wheelsdegree-velocity)

</details>





<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#라인트레이서">
        라인트레이서
        </a>
    </summary>

- [line_tracer_mode(mode)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#line_tracer_modemode)
- [line_left()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#line_left)
- [line_right()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#line_right)
- [line_both()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#line_both)
- [cross_left()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#cross_left)
- [cross_right()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#cross_right)
- [cross_forward()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#cross_forward)
- [cross_uturn()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#cross_uturn)
- [white_line_left()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_line_left)
- [white_line_right()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_line_right)
- [white_line_both()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_line_both)
- [white_cross_left()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_cross_left)
- [white_cross_right()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_cross_right)
- [white_cross_forward()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_cross_forward)
- [white_cross_uturn()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#white_cross_uturn)
- [line_gain(gain)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#line_gaingain)
- [line_speed(speed)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#line_speedspeed)
- [board_forward()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#board_forward)
- [board_left()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#board_left)
- [board_right()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/바퀴-움직임#board_right)

</details>


<br>

# [전방 LED](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED)

<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#전방-led-설정">
        전방 LED 설정
    </summary>

- [rgbs()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#rgbs)
- [rgbs(red, green, blue)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#rgbsred-green-blue)
- [rgbs(left_rgb, right_rgb)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#rgbsleft_rgb-right_rgb)
- [left_rgb(red, green, blue)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#left_rgbred-green-blue)
- [right_rgbs(red, green, blue)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#right_rgbsred-green-blue)
- [leds()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#leds)
- [leds(red, green, blue)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#ledsred-green-blue)
- [leds(left_rgb, right_rgb)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#ledsleft_rgb-right_rgb)
- [left_led(red, green, blue)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#left_ledred-green-blue)
- [right_led(red, green, blue)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전방-LED#right_ledred-green-blue)

</details>

<br>

# [소리](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#주파수-제어">
        주파수 제어
        </a>
    </summary>

- [buzzer(Hz)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#buzzerHz)
- [tempo(bpm)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#tempobpm)

</details>




<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#note-제어">
        NOTE 제어
        </a>
    </summary>

- [note(pitch)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#notepitch)
- [note(pitch, beats)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#notepitch-beats)

</details>






<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#멜로디-제어">
        멜로디 제어
        </a>
    </summary>

- [sound(sound_id)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#soundsound_id)
- [sound(sound_id, repeat)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#soundsound_id-repeat)
- [sound_until_done(sound_id)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#sound_until_donesound_id)
- [sound_until_done(sound_id, repeat)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#sound_until_donesound_id-repeat)
- [beep()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/소리#beep)

</details>




<br>



# [입출력모드](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드)

<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#입출력-설정">
        입출력설정
    </summary>

- [io_mode_a(mode)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#io_mode_amode)
- [io_mode_b(mode)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#io_mode_bmode)
- [output_a(value)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#output_avalue)
- [output_b(value)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#output_bvalue)
- [input_a()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#input_a)
- [input_b()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#input_b)
- [voltage_a()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#voltage_a)
- [voltage_b()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#voltage_b)

</details>


<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#그리퍼">
        그리퍼
    </summary>

- [open_gripper()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#open_gripper)
- [close_gripper()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#close_gripper)
- [release_gripper()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/입출력모드#release-gripper)

</details>

<br>



# [센서](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#근접-센서">
        근접센서
        </a>
    </summary>

- [left_proximity()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#left_proximity)
- [right_proximity()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#right_proximity)

</details>


<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#바닥-센서">
        바닥센서
    </summary>

- [left_floor()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#left_floor)
- [right_floor()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#right_floor)

</details>

<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#가속도-감지-센서">
        가속도 감지 센서
    </summary>

- [acceleration_x()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#acceleration_x)
- [acceleration_y()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#acceleration_y)
- [acceleration_z()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#acceleration_z)
- [tilt()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#tilt)

</details>

<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#조도센서">
        조도센서, 온도센서, 배터리
    </summary>

- [light()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#조도센서)
- [temperature()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#온도센서)
- [battery_state()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/센서#배터리)

</details>

<br>





# [전역 함수](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수)

<details>
    <summary><a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#해제-다중-작동-포트-출력-콜백-함수">
    해제, 다중 작동, 시리얼 포트 출력, 콜백함수</a></summary>

- [dispose()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#dispose)
- [parallel(function1, function2, ...)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#parallelfunction1-function2-)
- [parallel((function1, args1), (function2, args2), ...)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#parallelfunction1-args1-function2-args2-)
- [scan()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#scan)
- [set_executable(execute)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#set_executableexecute)

</details>


<details>
    <summary><a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#대기-함수">
    대기 함수
    </a></summary>

- [wait(milliseconds)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#waitmilliseconds)
- [wait_until(evaluate)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#wait_untilevaluate)
- [wait_until(evaluate, args)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#wait_untilevaluate-args)
- [wait_until_ready()](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#wait_until_ready)

</details>


<details>
    <summary><a href="https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#조건-함수">
    조건 함수</a></summary>

- [when_do(when, do)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#when_dowhen-do)
- [when_do(when, do, args)](https://github.com/RobomationLAB/Hamster-S_API_KR/wiki/전역함수#when_dowhen-do-args)

</details>













<br><br>
><a href="https://www.robomation.net" target="_blank">www.robomation.net</a><br>

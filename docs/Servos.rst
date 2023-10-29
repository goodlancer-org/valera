Servo motors
==================

Servo motors drive Valera and this is essential to set the up and test like it's show on the video below.

.. raw:: html

    <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/7wUNU5IKYxU?si=-xs0XWdKWBbhhZVB" 
    title="Valera robot YouTube video" frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>
    </iframe>

Servo motor is a motor with integrated movement sensor, usually it's a simple 
potentiometer, which allow to control the angle of the motor's rotation. 
Here's the scheme:

.. figure:: images/Servos/ServosScheme.png

    Servo Scheme

There're two types of servo motors: angle-controlled and speed-controlled.
Were we're going to discuss only first ones.

Angle servos are commonly called 180-degrees srvo, but usually their range is 
not 180d. It may be 120, 270 or 360 degress, depends of the srvo you buy. In our 
case it's around 120 degrees, so you always have to mind the position when placing a servo 
into your creation so it would use it's all potential.

Servos are operated by sending them serial pulses. The width of a pulse tell the motor 
to which angle to turn.

.. figure:: images/Servos/ServosSignal.png

    Servo Signal

In order to test or manually move servos if needed we use servo tester.

.. figure:: images/Servos/ServosTester.jpeg

    Servo Tester

You can plug several motors in it and control them at the same time. It is very helpful when 
you check your motor's angle range or check the correctness of your assembly.

When you need to controll your servos automatically you use a servo-controller. It's a small plate,
looking like that:

.. figure:: images/Servos/ServosController.jpg

    Servo Controller

Usually these plates receive PWM signal, but it maybe different for some of them. Check your plate's 
documentation. 

I hope this essay will help you to navigate through tough way of a robot creator.

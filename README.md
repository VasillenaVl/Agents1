using System;

namespace Area51
{
    public class Agent
    {
        public int Number { get; set; }

        public string SecurityLevel { get; set; }

        public string CurrentFloor { get; set; }

        //public string NewFloor { get; set; }

        public bool CallElevatorButtonPressed { get; set; }


        public bool InElevator { get; set; }

        public Agent(int agentNumber, string secLevel, string currentFloor)
        {
            this.Number = agentNumber;
            this.CurrentFloor = currentFloor;
            this.SecurityLevel = secLevel;
            this.InElevator = false;
        }

    }
}
